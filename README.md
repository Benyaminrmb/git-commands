
# Usefull git commands



## 1. Clone

`git clone <https://name-of-the-repository-link>`

## 2. Git branch

### Creating a new branch:

`git branch <branch-name>`

#### This command will create a branch locally. To push the new branch into the remote repository, you need to use the following command:

`git push -u <remote> <branch-name>`

### Viewing branches:
`git branch`

 or

`git branch --list`
### Deleting a branch:
`git branch -d <branch-name>`


## 3. Git checkout

`git checkout <name-of-your-branch>`

### create and switch to a branch at the same time:
`git checkout -b <name-of-your-branch>`

## 4. Git status

`git status`
## 5. Git add
### To add a single file:
`git add <file>`
### To add everything at once:
`git add -A`

## 6. Git commit

`git commit -m "commit message"`
## 7. Git push

`git push <remote> <branch-name>`
####  if your branch is newly created, then you also need to upload the branch with the following command:
`git push --set-upstream <remote> <name-of-your-branch>` 

or

`git push -u origin <branch_name>`

## 8. Git pull
`git pull <remote>`

## 9. Git revert
**first we need to use git `log --oneline`**

and then

`git revert 3321844`


>- shift + q to exit

## 10. Git merge
### First you should switch to the dev branch:
`git checkout dev`

### Before merging, you should update your local dev branch:
`git fetch`
### Finally, you can merge your feature branch into dev:
`git merge <branch-name>`


## Author

- [@benyaminrmb](https://www.github.com/benyaminrmb)
