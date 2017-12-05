# How to install Arc-Theme

## First

You should install GTK3.0 library on your linux system first.

For ubuntu 's install code is :

	apt-get install libgtk-3-dev gtk-engine-murrine

For fedora 's install code is :

	dnf install gtk3-devel gtk-murrine-engine

## Second

You need install auto-configure tool for next build task.

For ubuntu 's install code is :

	apt-get install autoconf automake pkg-config

For fedora 's install code is :

	dnf install autoconf automake pkgconfig

## Final

Clone this repository, and entry into the directory to run these code:

	./autogen.sh --prefix=/usr
	make install

### Notice:

Please use root permisson to do it.
