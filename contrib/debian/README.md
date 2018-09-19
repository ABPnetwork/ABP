
Debian
====================
This directory contains files used to package abpd/abp-qt
for Debian-based Linux systems. If you compile abpd/abp-qt yourself, there are some useful files here.

## abp: URI support ##


abp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install abp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your abpqt binary to `/usr/bin`
and the `../../share/pixmaps/abp128.png` to `/usr/share/pixmaps`

abp-qt.protocol (KDE)

