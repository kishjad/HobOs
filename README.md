hobos
========
A hobby operating system written in C++14. An experiment to see what use the new
C++14 standard features might be in an operating system kernel.


Building
--------
Install [scons](http://scons.org/) and run `scons`.


Running in a VM
---------------
Install [qemu](http://wiki.qemu.org/) and run `qemu-system-i386 hobos.iso`.


Running on Real Hardware
------------------------
I haven't tried this yet... but feel free to give it a go. `scons` generates a
`hobos.iso` which you should be able to burn to a CD or USB stick and boot
from.
