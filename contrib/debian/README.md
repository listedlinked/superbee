
Debian
====================
This directory contains files used to package superbeed/superbee-qt
for Debian-based Linux systems. If you compile superbeed/superbee-qt yourself, there are some useful files here.

## superbee: URI support ##


superbee-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install superbee-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your superbeeqt binary to `/usr/bin`
and the `../../share/pixmaps/superbee128.png` to `/usr/share/pixmaps`

superbee-qt.protocol (KDE)

