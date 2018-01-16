
Debian
====================
This directory contains files used to package dinerod/dinero-qt
for Debian-based Linux systems. If you compile dinerod/dinero-qt yourself, there are some useful files here.

## dinero: URI support ##


dinero-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dinero-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dinero-qt binary to `/usr/bin`
and the `../../share/pixmaps/dinero128.png` to `/usr/share/pixmaps`

dinero-qt.protocol (KDE)

