
Debian
====================
This directory contains files used to package herad/hera-qt
for Debian-based Linux systems. If you compile herad/hera-qt yourself, there are some useful files here.

## hera: URI support ##


hera-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hera-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your heraqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

hera-qt.protocol (KDE)

