
Debian
====================
This directory contains files used to package ltcld/ltcl-qt
for Debian-based Linux systems. If you compile ltcld/ltcl-qt yourself, there are some useful files here.

## ltcl: URI support ##


ltcl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ltcl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ltclqt binary to `/usr/bin`
and the `../../share/pixmaps/ltcl128.png` to `/usr/share/pixmaps`

ltcl-qt.protocol (KDE)

