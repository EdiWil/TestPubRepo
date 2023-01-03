# GIT_Befehle

## OTHER GIT commands

 1981  git branch PBMBSTK-2423
 1982  git branch -l
 1979  git branch --delete <branchname>

 1985  git checkout main
 1986  git checkout PBMBSTK-2423


## GIT Befehler vorgeschlagen von GitHub

…or create a new repository on the command line

```
echo "# TestRepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/EdiWil/TestRepo.git
git push -u origin main
```


…or push an existing repository from the command line

```
git remote add origin https://github.com/EdiWil/TestRepo.git
git branch -M main
git push -u origin main
```
