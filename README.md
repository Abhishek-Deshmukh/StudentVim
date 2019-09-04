# About StudentVim
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/Abhishek-Deshmukh)

Student vim is a set of plugins an setting useful for students to take notes Using markdown. It has a few personal setting which you can change if you want to change

#### Requirements
- [Neovim](https://github.com/neovim/neovim)
- [Plug](https://github.com/junegunn/vim-plug#neovim)

### Install Instruction
- `git clone https://github.com/Abhishek-Deshmukh/StudentVim`
- Open the file in vim and then in normal mode type `:source %`
- `:PlugInstall`
- Go to where the plugins were downloaded
- `cd` into the `youcompleteme` folder
- `$ ./install.py -all`
- It's ready

## Installed Plugins and how to use them

### [Nerd Tree](https://github.com/scrooloose/nerdtree)

This is a file system explorer.

When in normal mode press ,n to toggle it on and off.

Press ? for more details.

### [Goyo](https://github.com/junegunn/goyo.vim)

For distraction free writing.

When in normal mode press ,f to toggle it on and off.

### [Vim surround](https://github.com/tpope/vim-surround)

Vim surround is used for changing things around a word or a selection.

just type `cs"'` to replace the surrounding `"` with `'`. or for changing `()` to `[]` (`cs[(`).

### [Vim airline](https://github.com/vim-airline/vim-airline)

For the status bar.

### [Vim-commentary](https://github.com/tpope/vim-commentary)

Used for fast commenting and uncommenting

`gcc` to comment or uncomment the line you are on.

`gc` then the motion of the cursor (`gc4j` for 4 line down form where the coursor is)(`gcap` for the whole paragraph)

### [vim-solarized8](https://github.com/lifepillar/vim-solarized8)

For the theme

### [youcompleteme](https://github.com/ycm-core/YouCompleteMe)

Auto completion

### [vim-instant-markdown](https://github.com/suan/vim-instant-markdown)

This is for seeing the markdown preview on a you default browser(in github flavour).

## Some other features

- Removes the tex build files when you exit the document
- Syntax is matched with the file type automatically
- Automatically deletes any trailing while spaces
- Latex, HTML, Markdown, xml shortcuts
- `,c` for autocompile form most file documents.([To use this](https://github.com/Abhishek-Deshmukh/Compiler))
- `,p` to open the corresonding pdf file(if produced)
- `S` in normal mode set as replace all aliase

