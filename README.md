# vimfiles
## Provisioning vim

Do the following for provisioning:
    
```sh
wget https://raw.githubusercontent.com/ryanmackenziewhite/vimfiles/master/vimrc 
mv vimrc ~/.vimrc
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
vim +PluginInstall +qall
```
