# Sigma.vim

pics

You might have already seen NvChad, but you want a simpler config and be a Chad
too? Sigma.vim was made for you.

```sh
............................................................
............................... ... ........................
..................... ......'...,,.... .....................
...................  ..'''''',''';;;;'......................
................... ..',,;:::cclodxxdo;.....................
..................  ...''',,,;:ccllllc;.....................
..................   ...',;::::clllcc:,.....................
................... .... ............','....................
......................      ...      ..',,..................
......................... ...:;.....',,'....................
...................  .......'cl,.'......''..................
...................    ...........'..  .....................
...................             ....   .....................
...................           ...  .    ....................
.....................                 ......................
.....................                .......................
.....................               ...''...................
....................               ....';::,................
................'...              ....'';:clool:,...........
..........',,''.....             ....',;:ccccloodddl;.......
.......,;;;;,''......           ..',;:cloooooodoooodddl;'...
',,,;;:::;;;;,''''....         ...';:clloloooooddoodxxxxdddd
;:::::::::;;;,,,''...............';:cllllcllloooodddddddddoo
;;;;;;;;;;;;;;,,,'''......'''....',;::cccccllllllllllllllllc
,,,,,,,,,;;;;;;;,,,,,,,,,,,,;'...'',;:::ccllllllllccc::;;;;;
....'',,,,,,;;;;;;;;;;;;;;;;;,..',,;;:::cclllccccc::;;,''.''
......'''',,,,,;;;;;;;;;;;;::'..'',;;::::ccccc::::;,,,'.....
. ........'''',,,;;;;;;;;,;;;....'',,,;;;;;;;;;;,,,''....   
   ...........'',,,,,,;;;;;;;.....'''',,,,,,''''........    
    ............''''''''''''.............'............
```

## Why another Vim distribution

Most of these distributions are pretty complex, and usually happen to be a pain
to actually replace some base plugins.

## What is Sigma.vim

...

## Dependencies

- [NerdFont](https://github.com/ryanoasis/nerd-fonts)
- [Fzf](https://github.com/junegunn/fzf) - all the fuzzy finding
- [Ripgrep](https://github.com/BurntSushi/ripgrep) - for Fzf default config in Sigma
- [Fd](https://github.com/sharkdp/fd) - also for Fzf
- [Nnn](https://github.com/jarun/nnn) - default file picker, might be disabled / replaced
- [Npm](https://github.com/npm/cli) - for Mason / LSP
- [Kitty](https://github.com/kovidgoyal/kitty) or [Tmux](https://github.com/tmux/tmux) - for lazygit / dropdown terminal / nnn preview-tui
- [Lazygit](https://github.com/jesseduffield/lazygit) - lazygit integration
- [Python 3](https://www.python.org/) - Ultisnips for nvim-cmp

## Installation

Install vim-plug first:

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Install Sigma.nvim:

```sh
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/lua/sigma/init.lua --create-dirs \
       https://raw.githubusercontent.com/wmwnuk/sigma.nvim/main/lua/sigma/init.lua'
```

(This doesn't actually work yet)

## Configuration

...
