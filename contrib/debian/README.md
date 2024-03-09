
Debian
====================
This directory contains files used to package virsaid/virsai-qt
for Debian-based Linux systems. If you compile virsaid/virsai-qt yourself, there are some useful files here.

## virsai: URI support ##


virsai-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install virsai-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your virsai-qt binary to `/usr/bin`
and the `../../share/pixmaps/virsai128.png` to `/usr/share/pixmaps`

virsai-qt.protocol (KDE)

