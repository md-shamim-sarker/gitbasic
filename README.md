# gitbasic
## Initialization
```code
git init
```
## Present status
```code
git status
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