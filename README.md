# git-reflow-sandbox

## Installation

```
$ gem install reflow git_reflow
$ source ~/.zshrc
$ git reflow setup
Available remote Git Server services::
1. GitHub
2. BitBucket (team-owned repos only)
Which service would you like to use for this project? 
Please enter your GitHub username:
Please enter your GitHub password (we do NOT store this):

Your GitHub account was successfully setup!
```

## Use

Create Branch.
```
$ git reflow start develop
```

Send Pull Request.
```
$ git reflow review
```

Comment "LGTM" to Pull Request.

Merge Pull Request.
```
$ git reflow deliver
```
