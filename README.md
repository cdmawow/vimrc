Best vimrc for CoolCeph team, used for C/C++, Python, PHP and Go.

Enjoy it.

![alt tag](https://raw.github.com/coolceph/vimrc/master/screenshot-2.png)

# Install

```
git clone https://github.com/coolceph/vimrc.git ~/.vim
cd ~/.vim && ./install.sh
```

# ShortCuts

F2: Paste Model Switch

F3: NerdTREE Switch

F4: Tagbar Switch

F5: LineNumber Model Switch

F6: Whether Show Special Characters Such as Enter,Tab

F7: Update ctags

F8: Open undotree

F9: Enter multi cursor mode

F12: Mouse Model Switch (all or none)

SpaceSpace: Activate Unite Search Plugin

<C-n>/<C-p>: Switch between buffers.

<C-hjkl>: Switch between windows.

<C-c>: Quit vim without saving

The leader key is ','.

# Quick Commands

Ctags: Genrate ctags for pwd

Gotags: Genrate gotags for pwd

Hex/Asc: Swtich between Asc and Hex

Cswp: Clear *.swp

# FAQ

- My state line has strange characters

You should install the powerline fonts into your system and update the config of your terminal to use powerline fonts to display the Non-ASCII characters.
In the fonts dir, there is some powerline fonts you could choose.

- My vim is ugly, it seems some color are missing

You should set your env TERM=xterm-256color, you can do this by the following there ways:
1) run ~/.vim/install.sh, but you need run it every time when you login
2) set TERM=xterm-256color in your .bashrc or .zshrc
3) config your terminal tool
