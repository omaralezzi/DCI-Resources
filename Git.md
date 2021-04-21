# **Git & Github**

## [Install](https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-20-04) Git:

+ sudo apt update
+ sudo apt install git
+ git config --global user.name "Your Name"
+ git config --global user.email "youremail@domain.com"
+ git config --global core.editor "code --wait"
+ [Create SSH public key for GitHub](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
+ [GitHub Student Developer Pack](https://gist.github.com/LeandroDCI/b9f53690be5f2aaef2e93913bab5ff13)

<br>

## Creating a repository locally
+  `cd` path/to/parent/directory
+  `mkdir` projectName
+ `cd` projectName
+ `git init`
+ `tree -a` # to see the newly created invisible .git directory and its contents

## Creating a snapshot of your project

+  Make changes
+  `git status` # to see what files have been added, changed or deleted
+  `git diff` # to see what lines have been added, changed or deleted in modified files
+  Press `space bar` to show more diff information
+  Press `Shift-Q` to exit the diff program
+  `git add .`
+  `git commit`

## Linking a local repository to a remote repository on GitHub

+ Create an account on GitHub
+ Visit your repository page
+ Click on the New button to create a new repository on GitHub
+ DO NOT add any files (no README file, no .gitignore, no licence files)
+ Click on Create Repository
+ Copy the 3 lines:

> `git remote add origin git@github.com:<account_name>/<repo_name>.git` <br>
 `git branch -M main` <br>
 `git push -u origin main`
<br> 


 ## Forking a repository
+ Visit source project repository
+ Click on Fork
+ Select your person GitHub account


## Cloning a repository from GitHub to your local computer

 _In your browser:_

+ Visit the repository page on GitHub
+ Open the <> Code tab
+ Click on the green Code button
+ Copy the SSH url for the repository
 
 _In VS Code, on your local computer_

+ Open a new window
+ Open (create) a directory for the project
+ Open the Terminal pane
+ cd into the project directory
+ Paste the copied lines of bash code, and execute them

## Working with branches

+ `git branch`
+ `git branch -v`
+ `git branch newBranchName`
+ `git checkout existingBranchName`
+ `git branch -b new_branch_name`
+ `git branch --delete nameOfBranchToDelete`
+ `git branch -d nameOfBranchToDelete`


## Pull Requests

+ Fork the project repository on GitHub
+ Clone your fork to your local computer
+ Create a branch with a change-specific name
+ Make your changes
+ Commit your changes
+ Push your change-specific branch to your GitHub repository
+ Visit you GitHub repository page
+ Select the Pull Requests tab
+ Click on the Compare & Pull Request button
+ Enter any additional information
+ Click on Create Pull Request


## Merging branches

+ Pull collaborator's branch from GitHub, if necessary
+ `git checkout` \nameOfRecipientBranch
+ `git merge` \nameOfSourceBranch
+ Resolve any conflicts
    * Find lines with `<<<<<<< ======= >>>>>>>`
    * Decide which conflicting lines to keep, which to delete, which to change
    * Remove the lines with `<<<<<<< ======= >>>>>>>`
    * Commit the changes
+ Abort merge using `git merge --abort`

## Synchronizing with upstream repository
_On your local copy of your fork:_

+ `git checkout main`
+ `git pull upstream/main`


