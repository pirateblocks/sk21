
Debian
====================
This directory contains files used to package skulld/skull-qt
for Debian-based Linux systems. If you compile skulld/skull-qt yourself, there are some useful files here.

## skull: URI support ##


skull-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install skull-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vsyncqt binary to `/usr/bin`
and the `../../share/pixmaps/vsync128.png` to `/usr/share/pixmaps`

skull-qt.protocol (KDE)

