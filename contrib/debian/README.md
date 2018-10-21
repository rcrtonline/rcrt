
Debian
====================
This directory contains files used to package recruitd/recruit-qt
for Debian-based Linux systems. If you compile recruitd/recruit-qt yourself, there are some useful files here.

## recruit: URI support ##


recruit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install recruit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your recruitqt binary to `/usr/bin`
and the `../../share/pixmaps/recruit128.png` to `/usr/share/pixmaps`

recruit-qt.protocol (KDE)

