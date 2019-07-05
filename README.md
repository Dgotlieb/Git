# Git
Simple git starter

https://git-scm.com/downloads

-----------------------------------------------------

### Create a new directory where the git repository will live and cd into it:
$ mkdir mygitrepo

$ cd mygitrepo


### Initialize a brand new git repository
$ git init

### Check git status 
$ fit status

### Register git userand email
$ git config user.name "<YOUR_NAME>“

$ git config user.email "<YOUR_EMAIL>"

--------------------------------------------------

### Create a file with text:
$ echo Hello, World! > test_file.txt

### “To register” (stage) the file for committing we need to add it to git using
$ git add test_file.txt

### Commit the file to the repository
$ git commit -m "Add my first file"

--------------------------------------------------

### Create a branch:
$ git branch new_feature

### Get a list of all branches:
$ git branch

### Switch into another branch:
$ git checkout new_feature
  
### Modify a file:
$ echo Hello > test_file.txt

### Stage the file:
$ git add .

### Commit changes:
$ git commit -m “changed again"

### Print file content:
$ type test_file.txt

### Checkout to master:
$ git checkout master

### Print file content (again):
$ type test_file.txt

### Modify the file (again) this time in master:
$ echo Hi > test_file.txt

### Stage the file:
$ git add .

### Commit changes (again) this time in master:
$ git commit -m “changed again"

### Try to merge changes
$ git merge new_feature

### Add and commit changes after conflict fix
git commit -a -m “fixed conflicts"

--------------------------------------------------

### See commits history
$ git log

### Jump into a commit
$ git checkout <commit hash>
  
--------------------------------------------------

### Revert a commit
$ git revert <commit hash>





