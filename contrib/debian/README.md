
Debian
====================
This directory contains files used to package uleadd/ulead-qt
for Debian-based Linux systems. If you compile uleadd/ulead-qt yourself, there are some useful files here.

## ulead: URI support ##


ulead-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ulead-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your uleadqt binary to `/usr/bin`
and the `../../share/pixmaps/ulead128.png` to `/usr/share/pixmaps`

ulead-qt.protocol (KDE)

