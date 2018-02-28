Dotfiles for Noriki (a.k.a. Tencho)
====

    cp 'dotfilename'.dotfile ~/.'dotfilename'

# zshrc

When you use the zshrc.dotfile file, oh-my-zsh and zsh (ofcource) are required.

Sample on Ubuntu 16.04 environment:

    $ sudo apt install zsh
    $ git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
    $ cp zshrc.dotfile ~/.zshrc

# vimrc

When you use the vimrc.dotfile file, NeoBundle is required.

Sample on Ubuntu 16.04 environment:

    $ mkdir -p ~/.vim/bundle
    $ git clone https://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim
    $ cp vimrc.dotfile ~/.vimrc
    $ vim

The vimrc.simple.dotfile is a vimrc file for not installed NeoBundle.
