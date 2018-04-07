
Debian
====================
This directory contains files used to package GyMoneyd/GyMoney-qt
for Debian-based Linux systems. If you compile GyMoneyd/GyMoney-qt yourself, there are some useful files here.

## GyMoney: URI support ##


GyMoney-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install GyMoney-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your GyMoneyqt binary to `/usr/bin`
and the `../../share/pixmaps/GyMoney128.png` to `/usr/share/pixmaps`

GyMoney-qt.protocol (KDE)

