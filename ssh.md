# Recipes for SSH

## Create a SSH Key

´´´
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
´´´

## Config for Specific Key to Host

´´´
#Default GitHub
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa-specific
´´´
