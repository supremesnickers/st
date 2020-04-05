# st - the simple terminal

This is my personal build of st, the simple terminal by suckless. It has everything I need:
1. gruvbox-theme with switching between light and dark using F6
1. output scrollback with Shift+PageUp / Shift+PageDown or Shift+mousewheel
1. URL opening and copying (thanks to Luke Smith)
1. transparency
1. Jetbrains Font, with Emojis from Nerd Fonts
1. compatibility with ~/.Xresources file

## Emojis
If st crashes, when viewing emojis, make sure to install the package [libxft-bgra](https://aur.archlinux.org/packages/lbxft-bgra) from the AUR

## How to install
1. Clone the repository
```
git clone github.com/hashidan/st
cd st
```
1. then install it 
```
make
make install
```
