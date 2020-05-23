# Jacob's Build of the Simple X display locker by [suckless](https://tools.suckless.org/slock/)

## Patches

- [Capscolor](https://tools.suckless.org/slock/patches/capscolor/)

- [Message](https://tools.suckless.org/slock/patches/message/)

## Installation

```shell
git clone https://gitlab.com/Jacob_McDonnell/slock.git
cd slock
./configure
sudo make install
```

Users of Arch-based distros can install from the AUR, [slock-jacob-git](https://aur.archlinux.org/packages/slock-jacob-git/).

## Editing the Message

Edit config.h and change the message variable. You can also change the font by editing the font_name variable but make sure slock supports it by checking slock -f. The text color can also be changed by editing the text_color variable.
