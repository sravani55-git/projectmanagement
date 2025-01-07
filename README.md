Git is a version control system that helps you track changes in your code or files over time. It allows multiple people to work on a project without interfering with each other's work
 GITHUB is a platform that hosts Git repositories online. It provides a graphical interface and various collaboration tools for Git users.

key Concepts
Repository (Repo): A project that is being tracked by Git. It contains all the files and their change history.
Commit: A snapshot of the repository at a certain point in time.
Branch: A separate line of development. The default branch is typically called main or master.
Merge: The process of combining changes from different branches.
Clone: Copying a remote repository to your local machine.
Push: Sending your local changes to the remote repository (e.g Github).
Pull: Fetching and integrating changes from the remote repository into your local repository.
Configuring Git

1.	Set your username
    
    git config --global user.name "Your Name"

    
2.	Set your email
    
    git config --global user.email  you@example.com

    
3.	Check your configuration
    
    git config --list
    
    
git init
Initializes  a new Git repository in the current directory.


git status
Shows the status of your working directory and staging area (what files have been changed, added, etc.).

git add <filename>
Adds  a file to the staging area, preparing it for a commit. You can add multiple files or all files using ..
git add .

git commit -m "commit message"
Commits  the changes in the staging area with a descriptive message.
git commit -m "Initial commit"

git log
Shows  the commit history of the repository.

git diff
Shows  the differences between the working  directory and the staging area.

Cloning a Repository

1. Clone a repository from GitHub
    
    git clone https://github.com/username/repository-name.git
    

2. Navigate into the repository directory
    
    cd repository-name




Branching and Merging 
create a new branch when used with a branch name.
git branch branch1  # Create a new branch
git checkout branch1 # Switches to the specified branch.

git checkout Main
git merge branch1
Merges  the specified branch into the current branch.

git push origin <branch-name>
Pushes  your changes to a remote repository (on GitHub).
git push origin main

git push --set-upstream origin main
Pushes a new branch to the remote repository and sets it as the default remote branch.

git push --set-upstream origin branch1
Undoing Changes

4. GitHub Commands
Once your repository is initialized with Git, you can interact with GitHub using Git commands:




Setting up Github Repository
Create a new repository on Github
Link your local repository to the Github repository:
git remote add origin https://github.com/username/repository-name.git
Push to Github
After committing your changes locally, push them to Github with:
git push origin main
To get the latest changes from Github, use:
git pull origin main

