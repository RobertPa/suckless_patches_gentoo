# suckless_patches_gentoo
The suckless.org community provides minimalist free software which follows the Unix philosophy.
Those applications are configured by editing the source code before compilation.
I plan to collect patches for suckless software in this repository in a format which allows to use them with Gentoo's package management system Portage.
Patches provided here may be 1:1 copies of patch-files provided at www.suckless.org rewritten in a format suitable for Portage,
some may be changed or updated in addition, some may be my own.
In Gentoo, portage can apply patches to ebuilds before your package is compiled.
All a user has to do is to put a .patch file into an appropriate directory in /etc/portage/patches and emerging a package.
For more information see
https://wiki.gentoo.org/wiki//etc/portage/patches
and
http://suckless.org/
