dot files are managed using a bare git repository as described at https://news.ycombinator.com/item?id=11070797

```
git init --bare $HOME/.myconf
alias config='/usr/bin/git --git-dir=$HOME/.myconf/ --work-tree=$HOME'
config config status.showUntrackedFiles no
```
