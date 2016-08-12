arch-vita-toolchain-sdk
=======================

This repo contains all PKGBUILDs to create Arch packages
for the vita toolchain.

<package>-vita-host are packages needed to recompile the toolchain
arm-vita-eabi-<package> are toolchain components
arm-vita-lib-<package> are runtime native Vita libraries. It includes common 
libs as provided by Xerpi's vita-portlibs, see https://github.com/xerpi/vita_portlibs
and libraries made explicitely for the Vita.

Currently, Vita specific libraries include
- Xerpi's libftpvita, see https://github.com/xerpi/libftpvita
- Xerpi's libvita2d, see https://github.com/xerpi/libvita2d

For more info about the toolchain, tools and libs, see following links

https://github.com/vitasdk
https://github.com/xerpi
https://github.com/henkaku
