
Debian
====================
This directory contains files used to package nosd/nos-qt
for Debian-based Linux systems. If you compile nosd/nos-qt yourself, there are some useful files here.

## nos: URI support ##


nos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nosqt binary to `/usr/bin`
and the `../../share/pixmaps/nos128.png` to `/usr/share/pixmaps`

nos-qt.protocol (KDE)

