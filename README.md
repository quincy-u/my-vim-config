# my-vim-config 
For personal vim configuration

## Install vim plug (vim plugins manager)
(vim plug: https://github.com/junegunn/vim-plug)

###### (2021.8.8) For MacOS/Ubuntu (refer vim-plug website for windows)
Create and go to autoload
```
mkdir -p ~/.vim/autoload/
```
```
cd ~/.vim/autoload/
```
Download vim plug into autoload
```
wget https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## Install plugins
clone this repo and cd into repo

copy the vimrc file
```
cat vim_config > ~/.vimrc
```
open vim and input
```
:PlugInstall
```
restart vim and everything should work
