# To install just vim settings

```
cd ~
git clone https://github.com/johnrlive/vimrc-after.git
cd ~/vimrc-after
ln -sf `pwd`/vimrc.after ~/.vimrc.after
```

# To Install color scheme
https://github.com/altercation/solarized

```
cd ~/vimrc-after
ln -sf `pwd`/solarized.vim ~/.vim/colors
```

# If Using Yadr dotfiles 

Yadr Link: https://github.com/skwp/dotfiles

```
cd ~/.yadr
git pull -r
rake update
```
