
Debian
====================
This directory contains files used to package bakerd/baker-qt
for Debian-based Linux systems. If you compile bakerd/baker-qt yourself, there are some useful files here.

## baker: URI support ##


baker-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install baker-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bakerqt binary to `/usr/bin`
and the `../../share/pixmaps/baker128.png` to `/usr/share/pixmaps`

baker-qt.protocol (KDE)

