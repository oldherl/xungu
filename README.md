# xungu

`xungu` 寻孤 can identify orphaned packages from [archlinuxcn] that are currently installed on your system.

Packages in [[archlinuxcn]](https://github.com/archlinuxcn/repo) are sometimes dropped due to various reasons. However, pacman doesn't notify the user (me) about it. Continuing to use such packages may cause dependency incompatibility, security vulnerability, or waiting on an old version hopelessly. So I wrote this tool to identify those packages so that I can act accordingly.

This tool is intended to use only on an Arch Linux system with [archlinuxcn] repo enabled.

## Dependency
* python3
* pyalpm

## Usage
`$ ./xungu`
```
fqterm-qt5-git 0.9.10.1.1.g55d08df-1
    a terminal emulator used for Telnet-based BBS, with Telnet and SSH support
    Packaged by lilac (on behalf of Jiachen Yang) <farseerfc@gmail.com>
    Packaged at 2020-08-11 17:33:30
    Installed at 2020-08-23 15:33:09
nali-cli 2.1.4-2
    Parse geoinfo of IP Address without leaving your terminal
    Packaged by lilac (on behalf of imlonghao) <github@esd.cc>
    Packaged at 2021-04-21 07:50:14
    Installed at 2021-04-29 00:21:23
```

## License
GPL-3

