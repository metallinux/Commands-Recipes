# GPG Recipes

## List GPG Keys
```
$ gpg --list-secret-keys --keyid-format LONG
```


## Generate a GPG Key
```
$ gpg --full-generate-key
```

## Show in ASCII armor format

```
$ gpg --full-generate-key
# Prints the GPG key ID, in ASCII armor format
$ gpg --armor --export 3AA5C34371567BD2
```

