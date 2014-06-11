There are three supported Platforms:

Xilinx  :	Zynq, Microblaze
Linux   :	Userspace using UIO, spidev, and sysfs GPIO
Generic :	Skeleton

To build for Xilinx:

Export your SDK_Export folder:
dave@HAL9000:~/devel/git/ad9361/sw$ export SDK_EXPORT=path_to_your/SDK/SDK_Export/hw

Build for ZYNQ:
dave@HAL9000:~/devel/git/ad9361/sw$ make -f Makefile.zynq [clean]

Build for Microblaze:
dave@HAL9000:~/devel/git/ad9361/sw$ make -f Makefile.microblaze [clean]


To build for Linux:
dave@HAL9000:~/devel/git/ad9361/sw$ make -f Makefile.linux [clean]

To build the skeleton:
dave@HAL9000:~/devel/git/ad9361/sw$ make -f Makefile.generic [clean]
