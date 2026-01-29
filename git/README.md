# Install Git Bash

- https://git-scm.com/install/windows
- git clone to the l-h Repo

## Practie 01
- Open the Git bash cli and create folder with your name
- Do the below steps
```
echo "my new file" > newfile.txt
ls
git status
git add newfile.txt
cat newfile.txt
git status
git commit -m "new file"
git status

```

- **Git mv** move or rename files
- **Git log** display the commit history
- **Git diff** see the differences between commits
  
```
git mv newfile.txt newfile01.txt
git status
git commit -m "rename"
git log
git log --graph --decorate
git log --oneline
git diff 61f2e9a 55b1459

```
