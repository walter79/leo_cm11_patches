leo_cm11_patches
=================

These patches need to be added, if you want to build a fully-working CM11 for leo. There are patches for SDcard, button rotation, and one for the proper META-INF compiling. :)

for Meta-Inf  apply patch here:  /build/core/makefile

and add:   USE_SET_METADATA := false    to your boardconfig
