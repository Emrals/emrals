
Debian
====================
This directory contains files used to package emralsd/emrals-qt
for Debian-based Linux systems. If you compile emralsd/emrals-qt yourself, there are some useful files here.

## emrals: URI support ##


emrals-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install emrals-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your emrals-qt binary to `/usr/bin`
and the `../../share/pixmaps/emrals128.png` to `/usr/share/pixmaps`

emrals-qt.protocol (KDE)

