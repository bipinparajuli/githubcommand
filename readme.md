# Frequently used Github Command
Command | Description
---- | ----
git config --global user.name "username" | Set or Update username.
git config --global user.email "user@gmail.com" | Set or Update the email address with github account
git init | Create an empty Git repository or reinitialize an existing one
git add filename | Add a single file to the staging area
git add . | Add all files and directories to the staging area
git status | Check the status of the current repository
git commit -m "commit messege" | Add a single line messege while making commit in repository
git commit | Allow to add multi-line text to expalin change made
git log | View the changes made in repository
git diff | View the list of change made to repository
git rm dirname/filename | Remove files from the current working tree
git branch branch_name | Create a new branch
git checkout -b branch_name | Switch git branch
git branch | List all branches
git branch -a | List all remote branches
git branch -d branch_name | Delete a existing branch
git brach -D branch_name | Forcibly delete a branch despite its current status
git push origin --delete branch_name | Delete a remote branch
git merge branch_name | Combine specific branch into the main branch
git merge --abort | Abort a conflicting merge
git reset | Reset the conflicted files to a stable state
git remote add origin https://github.com/url | Add a remote repository
git push origin main | Push a change to remote repository
git pull | Pull changes from a remote repository
git merge origin | Merge a remote repository with local repository
git push -u origin new_branch | Push a new branch to remote repository

