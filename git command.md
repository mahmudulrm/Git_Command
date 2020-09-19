# Git connect from local computer :
###### Globel connection:
```bash
git config --global user.name "mahmudulrm"
git config --global user.email "mahmudulrm@gmail.com"
```
###### Check User_name and Mail:
```bash
git config --global --list
```

# Create a new repository on the command line:
```bash
echo "# Git_Command" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/mahmudulrm/Git_Command.git
git push -u origin master
```
# Push an existing repository from the command line

```bash
git remote add origin https://github.com/mahmudulrm/Git_Command.git
git branch -M master
git push -u origin master
```
# Added new files:
# Create a new repository on the command line:
```bash
echo "# Git_Command" >> README.md
git init
git status

git add -A or --all
git commit -m "git Command list"
git branch -M master
git remote add origin https://github.com/mahmudulrm/Git_Command.git
git push -u origin master
```

