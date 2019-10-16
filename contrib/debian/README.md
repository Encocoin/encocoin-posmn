
Debian
====================
This directory contains files used to package encocoind/encocoin-qt
for Debian-based Linux systems. If you compile encocoind/encocoin-qt yourself, there are some useful files here.

## encocoin: URI support ##


encocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install encocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your encocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/encocoin128.png` to `/usr/share/pixmaps`

encocoin-qt.protocol (KDE)

