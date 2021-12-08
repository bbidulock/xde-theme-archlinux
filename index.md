---
layout: default
---
[xde-theme-archlinux -- read me first file.  2014-09-12]: #

xde-theme-archlinux
===============

Package `xde-theme-archlinux-1.1.4` was released under CCPL:cc-by-nc-nd-3.0
license 2014-09-12.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
an Arch Linux theme.
This theme uses the Squared-blue style from the [`xde-styles`][11]
package.

The source for `xde-theme-archlinux` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-archlinux-1.1.4` package, released 2014-09-12.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-archlinux.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-archlinux` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-archlinux.git
    $> cd xde-theme-archlinux
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-archlinux` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following are the five wallpapers included in the theme:

![archlinux-aqua-vines.jpg](images/archlinux-aqua-vines.jpg "Wallpaper #1")
![archlinux-berry.jpg](images/archlinux-berry.jpg "Wallpaper #2")
![archlinux-ekisho-carbonite.jpg](images/archlinux-ekisho-carbonite.jpg "Wallpaper #3")
![archlinux-poolclouds.jpg](images/archlinux-poolclouds.jpg "Wallpaper #4")
![archlinux-simplyblack.jpg](images/archlinux-simplyblack.jpg "Wallpaper #5")



[1]: https://github.com/bbidulock/xde-theme-archlinux
[2]: https://github.com/bbidulock/xde-theme-archlinux/issues
[3]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/RELEASE
[4]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/NEWS
[5]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/TODO
[7]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/INSTALL
[9]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/LICENSE
[10]: https://github.com/bbidulock/xde-theme-archlinux/blob/master/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #