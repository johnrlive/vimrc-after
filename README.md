# To install just vim settings

```
cd ~
git clone https://github.com/johnrlive/vimrc-after.git
cd ~/vimrc-after
ln -sf `pwd`/vimrc.local ~/.vimrc.local
ln -sf `pwd`/vimrc.bundles.local ~/.vimrc.bundles.local
ln -sf `pwd`/aliases.local ~/.aliases.local
ln -sf `pwd`/gitconfig.local ~/.gitconfig.local
ln -sf `pwd`/tmux.conf.local ~/.tmux.conf.local
```

# To add ZSH configs

```
cd ~/vimrc-after
ln -sf `pwd`/zsh/configs/chpwd.zsh ~/.zsh/configs/post/chpwd/chpwd.zsh
```


# To Update Dotfiles 
link: https://github.com/thoughtbot/dotfiles

```
rcup
```

# To Install color scheme
coming soon...
