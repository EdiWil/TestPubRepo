# GIT_Befehle

this is a test mark

## OTHER GIT commands

```
git clone https://github.com/EdiWil/TestPubRepo.git TestPubRepo
git clone -o booyah
git config --global user.email "EdiWil@abc.de"
git config --global user.name "Edi Wil"
git status
git branch PBMBSTK-2423
git branch -l
git branch --list
git branch --merged
git branch --no-merged
git branch --all
git branch --delete <branchname>
git branch -d test
git branch -D test
git branch -d PBMBSTK-2423 
git branch --move furhter_commands furtherCommands
git remote -v
git log --decorate=full
git log --decorate --graph --all
git log --oneline --decorate
git switch PBMBSTK-2423 ??
git checkout main
git checkout -b PBMBSTK-2423
git checkout origin/main
git merge PBMBSTK-2423 
git add file.txt
git commit -m "Testing"
git commit -a -m "commit never to be published"
git push
git push origin opticalBugFixes
git pull --rebase=true
git fetch origin main:main
```

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
