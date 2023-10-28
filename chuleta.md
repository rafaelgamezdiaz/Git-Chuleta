# GIT - Chuleta

## Summary of frequently used commands

### Clone a repository

To clone a remote repository
````
    git clone url_repo
````

Note: It's possible that the remote repository requires credentials


example

````
    git clone https://github.com/rafaelgamezdiaz/Git-Chuleta.git
````

### List the local branches

````
    git branch
````

### List the remote repositorie url related with the local repository

````
    git remote -v
````

### List the local files which has been updated but not commited already

````
    git status
````

### Remove one filename from the updated list
Select the filename from the list of 'git status'
````
    git restore filename
````

#### Include all the updated files to the list to be commited

````
    git add -A
````

or

````
    git add .
````

### Commit changes

````
    git commit -m "Name of the commit"
````

### Store temporary the changes in an Stack
It permits to see que status of the project just as is was in the last commit. 

````
    git stash
````

### Recover all the changes in the stack

````
    git stash apply
````

### Create a new branch

This command creates a new branch as a clone of the actual branch
````
    git checkout -b new_branch_name
````

### Move to an existing branch

````
    git checkout branch_name
````

### Merge changes from another branch to actual branch

````
    git merge origin_branch_name
````

### Update actual branch with the contend of remote ofigin branch

````
    git pull
````

### Push your changes to remote branch

````
    git push
````

If the branch does not exist in remote already, then use this command:

````
    git push --set-upstream origin my_branch
````

### Update the information of remote branch in your local.

This command does not make merge or changes your local branch. Obly updates information of remote branches.

````
    git fetch
````


