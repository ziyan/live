Live Workstation Image
======================

This repository is used to build a debian live image.

Design
------

Partition layout:

* base live boot image (about 250MB)
* root overlay (luks encrypted)
* home overlay (luks encrypted)


Requirements
------------

Debian packages needed:

* live-build
* cryptsetup
* ansible


