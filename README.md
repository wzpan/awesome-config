awesome-config
===

My configs for awesome window manager, including my private settings and a customized theme.

## Dependencies

All of these dependencies can be installed via `apt-get` in Ubuntu system.

* [awesome](http://awesome.naquadah.org/wiki/Main_Page) >= 3.5. 
* [xfce4-appfinder](http://docs.xfce.org/xfce/xfce4-appfinder/start) for quickly search and launch applications.
* [wicd](https://launchpad.net/wicd) for network configuration.
* [kshutdown](http://kshutdown.sourceforge.net/) for poweroff/reboot/log off system.
* [xcompmgr](https://wiki.archlinux.org/index.php/Xcompmgr) to enable transparent effect.

## Features

* use konsole as default terminal
* use emacsclient as default editor
* use xcompmgr to enable transparent effect
* `modkey` + `e` : execute editor
* `modkey` + `g` : execute xfce4-appfinder
* `Alt` + `Shift_R` : switch dvorak and qwerty keyboard layouts

## Install

``` sh
$ cd $XDG_CONFIG_HOME     # $XDG_CONFIG_HOME is your awesome config folder
$ git clone https://github.com/wzpan/awesome-config.git .
```

Then press `ctrl` + `modkey` + `r` to restart awesome.
