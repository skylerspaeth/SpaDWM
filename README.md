# SpaDWM
Dynamic Window Manager(dwm) 6.2 with 3 patches applied:
- fullscreen
- vanitygaps
- dylanaraps' [openbox rounded corner patch](https://github.com/dylanaraps/openbox-patched), adapted for dwm

Several modifications were made for aesthetic purposes:
- status bar padding size increased slightly
- status bar font size increased slightly
- color font disabling code removed from `drw.c`, allowing [ttf-joypixels](https://www.archlinux.org/packages/community/any/ttf-joypixels/) emojis to be shown in status bar: REQUIRES [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) PATCH

![Screenshot](/screenshot.png)
