# dmenu
This is my patched version of dmenu.
The base version is directly from suckless.org.

## Patches
The list below shows the currently applied patches to this build.
- dmenu-border-4.9.diff
- dmenu-center-20200111-8cd37e1.diff
- dmenu-password-4.9.diff

## Installation
To install this package you can run several commands.

### AUR
If you're on Arch you can use the Arch User Repository.
For simplicity you can use a AUR-helper such as yay.
- `yay -S dmenu-tiyn-git`

Or you can clone it and run it by makepkg.
- `git clone https://aur.archlinux.org/dmenu-tiyn-git.git`
- `makepkg -sirc`

### MAKE
The most basic way is to clone the repository and then invoke make.
- `git clone https://github.com/tiyn/dmenu`
- `make clean install`
