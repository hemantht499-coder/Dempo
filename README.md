# Dempo
adharUsing Git involves interacting with your repositories through commands executed in a terminal or command prompt. Here's a breakdown of common Git commands and their uses: 
1. Initializing and Cloning Repositories: 

• git init: Initializes a new, empty Git repository in the current directory. This creates a hidden .git folder that stores all the repository's metadata. 

    git init

• git clone &lt;repository_url&gt;: Creates a local copy of an existing remote Git repository (e.g., from GitHub, GitLab, Bitbucket). 

    git clone https://github.com/user/repository.git

2. Managing Changes: 

• git add &lt;file_name&gt; / git add .: Stages changes for the next commit. git add &lt;file_name&gt; adds a specific file, while git add . stages all changes in the current directory and its subdirectories. 

    git add index.html
    git add .

• git commit -m "Commit message": Records the staged changes to the repository's history with a descriptive message. 

    git commit -m "Add initial project files"

• git status: Shows the current state of the working directory and staging area, indicating which files are modified, staged, or untracked. 

    git status

3. Working with Branches: 

• git branch: Lists all local branches. 

    git branch

• git branch &lt;new_branch_name&gt;: Creates a new branch. 

    git branch feature-branch

• git checkout &lt;branch_name&gt;: Switches to a different branch. 

    git checkout feature-branch

• git checkout -b &lt;new_branch_name&gt;: Creates a new branch and immediately switches to it. 

    git checkout -b new-feature

• git merge &lt;branch_to_merge&gt;: Integrates changes from one branch into the current branch. 

    git merge feature-branch

4. Interacting with Remote Repositories: 

• git remote add origin &lt;remote_repository_url&gt;: Connects your local repository to a remote repository, typically named "origin." 

    git remote add origin https://github.com/user/repository.git

• git push origin &lt;branch_name&gt;: Uploads your local commits to the specified remote branch. 

    git push origin main

• git pull origin &lt;branch_name&gt;: Downloads and integrates changes from the specified remote branch into your local branch. 

    git pull origin main

5. Viewing History: 

• git log: Displays the commit history of the current branch. 

    git log

These are some of the most fundamental Git commands. Git offers a vast array of commands for more advanced operations like reverting changes, rebasing, and managing submodules. 

AI responses may include mistakes.


Dempo 
