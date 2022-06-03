# gitbasic
## Initialization
```code
git init
```
## Present status
```code
git status
```
## Present status shortly
?? - Untracked files
A - Files added to stage
M - Modified files
D - Deleted files
```code
git status --short
```
## See git log
```code
git log
```
## See log content
```code
git show logkey
```
## Clone remote repository
```code
git clone [http link]
```
## Stage all
```code
git add --all
```
## Stage all
```code
git add -A
```
## Stage just folder content (Easy Form)
```code
git add .
```
## Stage all without deleted item
```code
git add *
```
## Stage a specific file
```code
git add one.txt
```
## Stage a specific file
```code
git add myFolder/two.txt
```
## Stage all .txt files
```code
git add *.txt
```
## Unstage all without deleted item
```code
git reset
```
## Unstage a specific file
```code
git restore fileName.extension
```
## Unstage all with deleted item
```code
git reset --hard
```
## Commit something
```code
git commit -m "summary"
```
## Rollback all thing
```code
git reset HEAD~
```
## Remove & stage that file
```code
git rm one.txt
```
## Remove a unstaged file forcefully
```code
git rm one.txt -f
```
## Remove cached (Delete two.txt but two.txt file stay in working directory with unstaged)
```code
git rm --cached two.txt
```
## Remove folder in recursive way
```code
git rm -r folderName
```
## Show all branches
```code
git branch
```
## Create a branch named development
```code
git branch development
```
## Navigate branch named development
```code
git checkout development
```
## Create a branch and navigate that branch at the same time
```code
git checkout -b branchName
```
## Merge main branch from inside other branch
```code
git merge main -m "message"
```
## Merge development branch from inside other branch
```code
git merge development -m "message"
```
## Merge development branch from inside other branch
```code
git merge development
```
## Delete a branch
```code
git branch -d branchName
```
## Push main repository local to remote
```code
git push origin main
```
## Push development repository local to remote
```code
git push origin development
```
## Fetch only changes at local from remote repository
```code
git fetch
```
## Fetch contents at local from remote repository
```code
git merge
```
## Fetch + Merge at local from remote repository
```code
git pull
```

# CMD Command
## Create a folder
```code
mkdir myFolder
```
## Navigate a folder
```code
cd myFolder
```
## Create a text file
```code
touch one.txt
```
## Folder Content Lists
```code
ls
```
## Present Working Directory
```code
pwd
```
## Clear Screen
```code
clear
```
## Back one folder
```code
cd ../
```

# Git Bash Modification
## Change title (Need a copy for backup)
```code
C:\Program Files\Git\etc\profile.d\git-prompt.sh
```
