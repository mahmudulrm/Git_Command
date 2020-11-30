# Git connect from local computer :
###### Globel connection:
```bash
git config --global user.name "username"
git config --global user.email "username@gmail.com"
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
git remote add origin https://github.com/username/Git_Command.git
git push -u origin master
```
# Push an existing repository from the command line

```bash
git remote add origin https://github.com/username/Git_Command.git
git branch -M master
git push -u origin master
```
# Added new files:
```bash
git init
git add -A or --all
git status
git commit -m "git Command list"
git branch -M master
git push -u origin master
```


#Git remote, fetch, merge, and pull

	git remote show origin
	git remote add abc new/location
	git fetch abc
	git remote show origin
	git branch -a
	
#show tracking branch (Local)
	git branch -a

#Git fetch (.git download, not change anything origin/master and local/master)
	git fetch

#git logs (oneline --name-only
	git log --oneline
	git log lg 

#git logs (grap
	git log --graph
	
	https://www.thegeekstuff.com/2014/04/git-log/