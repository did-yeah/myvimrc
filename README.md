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


Don't forget to dowload plugin when first install:

   ```vim
   :PluginInstall
   ```

If you removed som plugin type:

   ```vim
   :PluginClean
   ```
