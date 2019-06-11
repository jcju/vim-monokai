vim-monokai
===========

Vim doesn't support function highlighting for C/C++.

This is a simple solution of function highlighting & class highlighting for C/C++, with a Monokai theme maintained by [crusoexia/vim-monokai](https://github.com/crusoexia/vim-monokai). 

* Acknowledgement to [@Janosimas](https://stackoverflow.com/a/10140882/2753374).

Install
-------

```bash
mkdir -p ~/.vim/colors
```
    
Download the `colors/monokai.vim` file from the repo to `~/.vim/colors/`

Enable Theme
------------

Copy below command to your `~/.vimrc`:

```VimL
syntax on
colorscheme monokai
```

Eenable function highlight for C/C++
------------------------------------

```bash
mkdir -p ~/.vim/syntax
```

Copy c.vim to `~/.vim/syntax/`, and replace the existing file if needed.

The syntax rule will be applied to *.c, *.cc, *.cpp files.


