# Build Debian 12 Bookworm RootFS
[![Build Debian RootFS](https://github.com/ss0snaa/create-debian-rootfs/actions/workflows/build-debian-rootfs.yml/badge.svg)](https://github.com/ss0snaa/create-debian-rootfs/actions/workflows/build-debian-rootfs.yml)

Build RootFS for Debian 12 Bookworm armhf
Board: [Orangepi PC Plus](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-PC-Plus.html)

### Requirements
* Linux system
* http://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html[POSIX-sh] compatible shell (e.g. Busybox ash, dash, ZSH, bash, …)
* common userland with `chroot`, `getopt`, `grep`, `sed`, `sha256sum`, `wget` (e.g. from Busybox, GNU coreutils, …)
* `tar` (full-blown)
