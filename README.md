# dmenu

This is my patched version of dmenu.
The base version is directly from suckless.org.
This belongs to my larbs installation script, meaning it's supposed to work in the environment of the larbs-base-installation.

## Patches

The list below shows the currently applied patches to this build.
- dmenu-border-4.9.diff (adds a border)
- dmenu-center-20200111-8cd37e1.diff (adds option to center dmenu)
- dmenu-fuzzymatch-4.9.diff (adds option to fuzzy matching)
- dmenu-password-4.9.diff (adds option to hide input)

## Installation

The most basic way is to clone the repository and then invoke make.
- `git clone https://github.com/tiyn/dmenu`
- `make clean install`
