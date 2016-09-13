# Parity debian package

These are the files used for building the debian package. It is a rebuild from the original Ethcore package, basically a combination of `dpkg -X` and `dpkg -e` commands.

You can rebuild the package by running:

`dpkg -b parity-rasp_1.3.0-0_armhf`

Note that parity binary is compressed as of github file size limit.

This deb package is part of the custom ethereum node raspbian image:

https://github.com/diglos/pi-gen
