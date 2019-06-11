vim-monokai
===========

Monokai color scheme with function & class highlight for C/C++. 

* Acknowledgement to [crusoexia/vim-monokai](https://github.com/crusoexia/vim-monokai). 
* Acknowledgement to [@Janosimas](https://stackoverflow.com/a/10140882/2753374).

Install
-------

```bash
mkdir -p ~/.vim/colors
```
    
Download the `colors/monokai.vim` file from the repo to `~/.vim/colors/`

Usage
-----

Copy below command to your `~/.vimrc`:

```VimL
syntax on
colorscheme monokai
```

To enable function highlight for C/C++:

```bash
mkdir -p ~/.vim/syntax
```

Copy c.vim to `~/.vim/syntax/`, and replace the existing file if needed.

It will be applied to *.c, *.cc, *.cpp files.


