
Debian
====================
This directory contains files used to package unoded/unode-qt
for Debian-based Linux systems. If you compile unoded/unode-qt yourself, there are some useful files here.

## unode: URI support ##


unode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install unode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your unode-qt binary to `/usr/bin`
and the `../../share/pixmaps/unode128.png` to `/usr/share/pixmaps`

unode-qt.protocol (KDE)

