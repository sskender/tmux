# tmux

Tmux configuration

## Quickstart

```bash
# backup old configuration (optional)
mv ~/.tmux.conf ~/.tmux.conf.bkp

# clone repository
cd ~/Documents
git clone git@github.com:sskender/tmux.git

# link tmux file
ln -s ~/Documents/tmux/tmux.conf ~/.tmux.conf

# update
cd ~/Documents/tmux
git pull
```

Reload tmux config:

```txt
[Ctrl-B] :source ~/.tmux.conf
```
