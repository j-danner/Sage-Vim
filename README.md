### Vim plugin for working with SageMath

> Note: this Plugin is based on the one by [saliola](https://github.com/saliola/sage-vim) and is only differing to the extent of not depending on [tmux](https://tmux.github.io/) and [vim-tbone](https://github.com/tpope/vim-tbone). Instead it offers a REPL interface using [repl.nvim](https://gitlab.com/HiPhish/repl.nvim).


Syntax highlighting:
- Uses the default syntax highlighting for python files, except that the
  docstrings use some RST highlighting
- This is done by creating a syntax file in after

Folding:
- modified the standard python folding to fold documentation strings
