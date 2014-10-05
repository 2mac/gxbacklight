gxbacklight
===========

GTK Frontend to xbacklight

This project was created with the purpose of being included in LXDE, since LXDE
was lacking a graphical backlight setting (thus relying on the command line).
Feel free to include it in your own desktop environment or use it to replace
your existing backlight setting manager.

gxbacklight follows a keep-it-simple design philosophy. It will have only the
amount of features needed in order to make it a complete product; nothing more.

Installation
------------

### Dependencies

Package    | Description                                   | Purpose
---------- | --------------------------------------------- | ---------------------
xbacklight | RandR-based backlight control application     | Backend functionality
gtk2       | GObject-based multi-platform GUI toolkit (v2) | Graphics toolkit

### Installation Steps

gxbacklight follows the GNU build process. Installation is as follows:

    $ ./autogen.sh
    $ ./configure
    $ make
    # make install

License
-------

gxbacklight is [free software][1], released under the terms of version 3 of the
GNU Affero General Public License. See [COPYING][2] for more details.

[1]: http://gnu.org/philosophy/free-sw.html
[2]: COPYING
