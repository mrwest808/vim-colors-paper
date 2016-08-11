Paper Theme

===================

Forked from [PaperColor](https://github.com/vim-scripts/PaperColor.vim). Plus some modification of my own.

Light & Dark color schemes for **Vim** terminal editor and **gVim**

Inspired by Google's Material Design

Improve code readability; great for presentation

Currently designed for these file types:  C, C++, Java, Makefile, CMake, Bash, VimL, Golang, JavaScript, JSON, HTML, XML, Python, Ruby, Markdown, DTrace, PlantUML, SQL/MySQL, Octave/MATLAB, R, PHP, Perl, LUA,  NGINX, Yaml, Dosini, reStructuredText

## Screenshots

![theme-toggle](./theme-toggle.png)

![airline-theme](./airline-theme.png)

## Installation

Place 'paper.vim' file into 'colors' folder within your Vim directory, e.g. `~/.vim/colors/`

Or simply use a plugin manager like [vim-plug](https://github.com/junegunn/vim-plug) (recommended for easy `:PlugInstall`):

    Plugin 'ashfinal/vim-colors-paper'

Then, put this in your `~/.vimrc`

```VimL
set t_Co=256   " This is may or may not needed.

set background=light
colorscheme paper
```

Or using the dark version:

```VimL
set background=dark
colorscheme paper
```

To switch to dark or light variant during session: `:set background=dark` or `:set background=light`

To quickly toggle between them, use [vim-unimpaired](https://github.com/tpope/vim-unimpaired)'s keymap `cob`