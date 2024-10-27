# myvimrc

This repo if for sharing my .vimrc among various computers.
It is intended for personal use.

As of now it is broken. It should not be used.

first git clone the repo in your home dir:

   ```bash
   ~ $ git clone https://github.com/did-yeah/myvimrc.git
   ```

A symbolic link must be created for .vimrc in your home dir:

   ```bash
   ~ $ ln -s ~/myvimrc/myvimrc .vimrc
   ```

Install vundle:

   ```bash
   git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
   ```

Don't forget to dowload plugin when first install:

   ```vim
   :PluginInstall
   ```

If you removed some plugin:

   ```vim
   :PluginClean
   ```
