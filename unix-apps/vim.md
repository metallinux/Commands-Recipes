# Vi/Vim/Nvim Recipes

## Save with sudo

```
:w !sudo tee %
```

## Edit Remote files

```
vim scp://remoteuser@server.tld//absolute/path/to/document
:e scp://remoteuser@server.tld//absolute/path/to/document #New Buffer
:tabe scp://remoteuser@server.tld//absolute/path/to/document #New tab
```
