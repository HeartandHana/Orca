# Tutorial GIT by Somchai H.
# Content
[Config](##config)

[Create GIT](##create-git)

## config
```
git config --global user.name SomchaiH
git config --global user.email somchaih@isd.th.ibm.com
git config --global --list
```
## create GIT
```
git init myproject
``` 
## exception
```
create file name .gitignore
```
## add file
```
git add -A

git  commit -a -m "Message"
```
## check status
```
git status
git log
git log --oneline
git log --oneline --decorate
git log --oneline --decorate --graph
git log --stat
git log --grep="Message"
git log --after="2017-11-11"
git log --before="2017-11-11"
git log --author=somchai
```
## checkout
```
git checkout COMMIT6DIGIT
git checkout HEAD~2
git checkout master
```
## remove
```
git rm --cache "filename"
```
## delete untrack file
```
git clean -n
git clean -df
```
## branch
```
git chekout <branch name, commit id>
git checkout -b test
git checkout <branch name> <file name>
```
## GIT reset
```
git reset --hard <commit id>
git reset --soft <commit id>
git reset --mixed develop
```
## GIT marge
```
git marge --no--ff feature
git marge feature
git diff feature
```
## GIT remote
```
git remote add origin <url>
gti remote -v
```
## push
```
git push origin master
```
## pull, fetch, merge
```
git fetch -all
git marge origin/master
git pull origin master

git clone <url>
```
