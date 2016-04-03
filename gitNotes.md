BIS180L
Git Notes

Initiate repository: git init
Current state of project: git status ; run regularly to keep track of file
Add file to staging area: git add filename
Store staged changes with message describing what we added:
git commit -m desription in quotes

add multiple files in working directory using wildcard
git add apostrophe *fileextension apostrophe

add many files: git commit -m Add all files
see what changes have been made: git log
Push to git: git push -u source default localbranchname
Check for changes on GitHub repository and pull down any new changes:
git pull origin master

Show what is different: git diff
Add head for most recent commit: git diff HEAD

Unstage files: git reset

