dotfiles-vim
============

## Install
```
$ git clone https://github.com/jarinosuke/dotfiles-vim.git
$ cd dotfiles-vim
$ git submodule update -i
$ cd .vim/bundle/vimproc; make; cd -
$ ln -s `pwd`/{.vim,.vimrc,.vimrc.plugins} ~/
```

And do `:NeoBundleInstall` in vim
