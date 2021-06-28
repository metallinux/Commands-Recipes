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
$ gpg --armor --export 3AA5C34371567BD2
```

## Export Public and Private Key

```
$ gpg --output public.pgp --armor --export username@email
$ gpg --output private.pgp --armor --export-secret-key username@email

```

## Remove Passphrase on Private Key

```
$ gpg --list-secret-keys
$ gpg --edit-key XXXX 
gpg> passwd 
```



