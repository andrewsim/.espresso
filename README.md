# Shell

Install [zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH).

Install [prezto](https://github.com/sorin-ionescu/prezto).

Add the following modules into `.preztorc`:
```
  'git' \
  'syntax-highlighting' \
  'history-substring-search'
```

Change the keybinding to `vi`:
```
zstyle ':prezto:module:editor' key-bindings 'vi'
```

Change the theme to `agnoster`:
```
zstyle ':prezto:module:prompt' theme 'agnoster'
```

# tmux

Install tmux.

Install [tmux plugin manager](https://github.com/tmux-plugins/tpm).

Link `.tmux.conf`:
```
ln -s ~/sandbox/.espresso/.tmux.conf ~/.tmux.conf
```

# git

Link `.gitconfig`:
```
ln -s ~/sandbox/.espresso/.gitconfig ~/.gitconfig
```


