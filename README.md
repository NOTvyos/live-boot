[//]: # (DISCLAIMER tE4AWE_AQahaxUGUpugu BEGIN)

> [!CAUTION]
> This project is an **independent fork of VyOS®**.
> It is **not affiliated with, endorsed by, or sponsored by VyOS Networks Corporation** by any means.
> VyOS® is a registered trademark of VyOS Networks Corporation.

[//]: # (DISCLAIMER tE4AWE_AQahaxUGUpugu END)

# VyOS live-boot

This package is required (even in 1.4) to make the entire system boot.

This is a clone of the Debian package extending it with features required to make
our system boot. It mount's the VyOS config directories during system startup.
See https://github.com/vyos/live-boot/blob/current/components/9990-vyos.sh

## Ideas

The main idea is to drop this fork and consume Debian upstream live-build package
and add our required files to vyos-build chroot directory
