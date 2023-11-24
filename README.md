# Git-Aliases
This is a public repository providing my preferred git aliases

Updated git aliases on my local machine

## Git aliases added
```sh
### Git status shorthand
git config --global alias.st status
### Git commit shorthand
git config --global alias.cm 'commit -m'
### Git add, commit, and push in one command
git config --global alias.amp '!f() { git add -A && git commit -m "$1" && git push; }; f'
```

## Ubuntu aliases added

`docker-compose` is a long command, thus, it should be replaced with `dc`.

To do so, you should edit the `~/.bashrc` file, which can either be done manually or programmatically like this:
```sh
# Add the alias to the `~/.bashrc` file 
echo 'alias dc="docker-compose"' >> ~/.bashrc
# Save changes
source ~/.bashrc
```
