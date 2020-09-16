# Recpes for GIT


## Clone a Repo
```
git clone -b <branch> remote_repository_URL
```

## Uplodad Local to Remote
```
# Sets the new remote
$ git remote add origin remote_repository_URL
# Verifies the new remote URL
$ git remote -v
# Pushes the changes in your local repository up to the remote repository you specified as the origin
$ git push origin master
```

## Set Git to Sign with GPG Keys
```
git config --global user.signingkey 3AA5C34371567BD2
```

## Change Message or data after Commit but before Push
```
git commit --amend
```
