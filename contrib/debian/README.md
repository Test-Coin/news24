
Debian
====================
This directory contains files used to package News24d/News24-qt
for Debian-based Linux systems. If you compile News24d/News24-qt yourself, there are some useful files here.

## News24: URI support ##


News24-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install News24-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your News24qt binary to `/usr/bin`
and the `../../share/pixmaps/News24128.png` to `/usr/share/pixmaps`

News24-qt.protocol (KDE)

