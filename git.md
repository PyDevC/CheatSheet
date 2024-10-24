#Git
***
view all your settings and where they are coming from.
```bash
git config --list --show-origin
```
setting username and email
```bash
git config --global user.name "<Name>"
git config --global user.email <email>
```
This will configure the default text editor that will be used when git needs you to type in commit message.
```bash
git config --global core.editor <Name>
```
To name main as default branch 
```bash
git config --global init.defaultBranch main
```
To initialize the directory as git repository
```bash
git init
```
To clone a repository from GitHub
```bash
git clone <url>
```
To check which files are in which state
```bash
git status
```
To Track the file
```bash
git add <filename>
```
To see what you have changed but not yet staged.
```bash
git diff
```
To see what you've staged
```bash
git diff --staged
```
Launches default text editor to commit message
```bash
git commit
```
To delete file and stage the deleted change.
```bash
git rm <filename>
```
If you want to rename a file in Git to make a track of it else it will cause an error.
```bash
git mv <file_from> <file_to>
```
Lists the commits made in that repository in reverse chronological order.
```bash
git log
```
When staged new changes it commits in previous commit.
```bash
git commit --amend
```
To unstage the file
```bash
git reset HEAD <filename>
```
To unmodify changes made in the file.
```bash
git checkout -- <filename>
```
It lists shortnames of each remote handle
```bash
git remote
```
Shows Url for the shortnames of remote handles
```bash
git remote -v
```
To add new remote git repository as shortnames
```bash
git remote add <shortname> <url>
```
To get data from your remote projects.
```bash
git fetch <remote>
```
To fetch and automatically merge into local
```bash
git pull
```
To push it upstream
```bash
git push <remote> <branch>
```
To inspect remote repo
```bash
git remote show <remote>
```
Creating new branch 
```bash
git branch <branch>
```
Moves HEAD pointer to other branches
```bash
git checkout <branch>
```
To merge branch to main
```bash
git merge <branch>
```
***
## Config for .gitignore file
```bash
*.a # ignores all .a files
*a # ignores all files ending with a
!lib.a # track lib.a even if *.a is set to ignore
/TODO # ignore TODO files
build/ # ignore all files in build directory
doc/*.txt # ignore all with .txt in doc directory but not in subdirectory
doc/**/*.pdf # ignore all .pdf files even in subdirctory
```

