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

# NeoVim

Install neovim.

Install [dein.vim](https://github.com/Shougo/dein.vim).
```
curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
sh ./installer.sh ~/.config/nvim/bundle
```

Link `.init.vim`:
```
ln -s ~/sandbox/.espresso/nvim/init.vim ~/.config/nvim/init.vim
```
