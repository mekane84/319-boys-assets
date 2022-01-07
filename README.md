# 319-boys-assets
Assets for 319-boys

### Fix email setting for committing locally
go to github -> settings -> Emails
then either uncheck "Keep my email address private"
or, grab email on this page that looks like this:
99999999+username@users.noreply.github.com and modify
```
git config user.email "99999999+username@users.noreply.github.com"
git commit --amend --reset-author
```
if intellij opens vim window, type control-c or control-x and then type ":qa" and press enter 
