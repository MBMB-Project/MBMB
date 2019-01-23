
Debian
====================
This directory contains files used to package mbmbd/mbmb-qt
for Debian-based Linux systems. If you compile mbmbd/mbmb-qt yourself, there are some useful files here.

## mbmb: URI support ##


mbmb-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mbmb-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mbmbqt binary to `/usr/bin`
and the `../../share/pixmaps/mbmb128.png` to `/usr/share/pixmaps`

mbmb-qt.protocol (KDE)

