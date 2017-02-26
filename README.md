# OpenBSD on Apu2

The idea of this repo is to setup an [APU2](http://pcengines.ch/apu2c4.htm) with [OpenBSD](http://openbsd.org) as OS, for
a FW/GW/AP box at home (or maybe a company).

## Usage

Assuming that you already have OpenBSD installed on your APU2 with just an internet connection, you can do this:

```
# cd /tmp
# ftp -V https://raw.githubusercontent.com/gonzalo-/apu2_openbsd/master/Makefile
# make apu2
..................
..................
... some stuff ...
..................
..................
[+] All done, you can reboot now.
# reboot 
```
