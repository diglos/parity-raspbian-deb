# Parity debian package for Raspberry Pi 

These are the files used for building the debian package. It is a rebuild from the original Ethcore package for Ubuntu x64, basically a combination of `dpkg -X` and `dpkg -e` commands.

You can rebuild the package by running:

`dpkg -b parity-rasp_1.3.0-0_armhf`

Note that Parity binary is compressed as of Github file size limit.

This deb package is part of the custom Ethereum node Raspbian image for Raspberry Pi:

https://github.com/diglos/pi-gen
