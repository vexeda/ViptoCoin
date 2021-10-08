
Debian
====================
This directory contains files used to package viptocoind/viptocoin-qt
for Debian-based Linux systems. If you compile viptocoind/viptocoin-qt yourself, there are some useful files here.

## viptocoin: URI support ##


viptocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install viptocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your viptocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

viptocoin-qt.protocol (KDE)

