
Debian
====================
This directory contains files used to package katkoynd/katkoyn-qt
for Debian-based Linux systems. If you compile katkoynd/katkoyn-qt yourself, there are some useful files here.

## katkoyn: URI support ##


katkoyn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install katkoyn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your katkoyn-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

katkoyn-qt.protocol (KDE)

