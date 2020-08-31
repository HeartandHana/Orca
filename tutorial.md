# Tutorial GIT by Somchai H.
# Content
[Config](##config)

[Create GIT](##create-git)

[Exception](##exception)

[Add file](##add-file)

[Check status](##check-status)

[Check out](##checkout)

[Remove](##remove)

[Delete untrack file](##Delete-untrack-file)

[Branch](## Branch)

[GIT reset](##GIT-Reset)

[GIT marge](##GIT-marge)

[GIT remote](##GIT-remote)

[Push](##push)

[Pull, fetch, merge](Pull-fetch-merge)


## Config
```
git config --global user.name SomchaiH
git config --global user.email somchaih@isd.th.ibm.com
git config --global --list
```
## Create GIT
```
git init myproject
``` 
## Exception
```
create file name .gitignore
```
## Add file
```
git add -A

git  commit -a -m "Message"
```
## Check status
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
## Checkout
```
git checkout COMMIT6DIGIT
git checkout HEAD~2
git checkout master
```
## Remove
```
git rm --cache "filename"
```
## Delete untrack file
```
git clean -n
git clean -df
```
## Branch
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
## Push
```
git push origin master
```
## Pull fetch merge
```
git fetch -all
git marge origin/master
git pull origin master

git clone <url>
```
