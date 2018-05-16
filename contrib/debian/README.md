
Debian
====================
This directory contains files used to package ximantd/ximant-qt
for Debian-based Linux systems. If you compile ximantd/ximant-qt yourself, there are some useful files here.

## ximant: URI support ##


ximant-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ximant-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ximantqt binary to `/usr/bin`
and the `../../share/pixmaps/ximant128.png` to `/usr/share/pixmaps`

ximant-qt.protocol (KDE)

