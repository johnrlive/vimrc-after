# To install just vim settings

```
cd ~
git clone https://github.com/johnrlive/vimrc-after.git
cd ~/vimrc-after
ln -sf `pwd`/vimrc.after ~/.vimrc.after
ln -sf `pwd`/vundles.after ~/.yadr/vim/.vundles.after
```

# To Install color scheme
Solarized: https://github.com/altercation/solarized

```
cd ~/vimrc-after
ln -sf `pwd`/solarized.vim ~/.vim/colors
```

# To Add Custom VIM Plugins
YADR comes with a dead simple plugin manager that just uses vundles and submodules, without any fancy config files.

Add a plugin

    yav -u https://github.com/airblade/vim-rooter

Delete a plugin 

    ydv -u airblade/vim-rooter

The aliases (yav=yadr vim-add-plugin), (ydp=yadr vim-delete-plugin) and (yuv=yadr vim-update-all-plugins) live in the aliases file.
You can then commit the change. It's good to have your own fork of this project to do that.

# To Add Custom Aliases
Lots of things we do every day are done with two or three character mnemonic aliases. Please feel free to edit them:

alias edit
```
ae
```

alias reload
```
ar 
```

# To Update Yadr dotfiles 
Yadr: https://github.com/skwp/dotfiles

```
cd ~/.yadr
git pull -r
rake update
```
