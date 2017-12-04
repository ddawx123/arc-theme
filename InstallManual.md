# How to install Arc-Theme

## First

You should install GTK3.0 library on your linux system first, for ubuntu 's install code is :

	apt-get install libgtk-3-dev

## Second

You need install auto-configure tool for next build task, for ubuntu 's install code is :

	apt-get install autoconf

## Final

Clone this repository, and entry into the directory to run these code:

	./autogen.sh --prefix=/usr
	make install

### Notice:

Please use root permisson to do it.
