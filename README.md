# i. What is Version Control?

Version control is a system that helps track changes made to files and code over time. It allows developers to manage different versions of a project and work collaboratively without conflicts.


# ii. Importance of Version Control

 a. Tracks changes to code or files.
 b. Helps teams collaborate smoothly.
 c. Allows rolling back to previous versions.
 d.  Supports experimenting with new features using branches.


# iii. What is Git?

Git is a distributed version control system. It allows developers to save snapshots of their project, switch between versions, and collaborate easily. It works from the command line and runs locally on your computer.


# iv. What is GitHub?

GitHub is a cloud-based platform where Git repositories can be hosted. It provides tools for collaboration, issue tracking, pull requests, and version management, all via a web interface.


# v. Difference Between Git and GitHub

1. Git is a local version-control tool you install and run on your computer, while GitHub is a remote hosting platform where Git repositories live online.  
2. Git is primarily command-line based (though GUIs exist); GitHub offers a web interface plus optional CLI tools.  
3. Git was created by Linus Torvalds in 2005; GitHub is owned by Microsoft (acquired in 2018).  
4.  Git can work completely offline after installation; GitHub requires an internet connection to push, pull, or collaborate.


# vi. Git & GitHub Setup for Beginners

1. Install Git
   - Download from [git-scm.com](https://git-scm.com)
   - Confirm installation: `git --version`

2. Configure Git

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

3. Initialize Repository

mkdir git_setup
cd git_setup
git init

4. Create and Commit Files

touch README.md
git add README.md
git commit -m "Initial commit"

5. Push to GitHub

Create a new repository on GitHub.

git remote add origin https://github.com/yourusername/git_setup.git
git push -u origin main
