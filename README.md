See the README in https://github.com/wagle/addnas for a master index of repos.

This repo contains the information needed to construct a cross-compiling build machine for the ADDNAS.

The procedure is to:

(1) Install Fedora 13 from LIVE cdrom image.

(2) Using yum, install the list of RPM's in README.packages.

(3) Unpack the tarballs in opt/ to /opt on the build machine.  Notice that one of the unpacks directly, and one unpacks to opt/.  I didnt correct that because I wanted to keep the original tarballs.

NOTE:  I didn't upgrade the RPM's on the build machine.  That might work.  Or it might not.  Autoconf in addnas_source is pretty brittle.

You should now be able to build a linux distribution from https://github.com/wagle/addnas_source
