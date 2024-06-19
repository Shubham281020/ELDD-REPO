obj-m = gpio-intr.o

modules :
	make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C /home/shubhaam/Desktop/DESD_c/linux/ M=`pwd` modules

clean : 
	make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C /home/shubhaam/Desktop/DESD_c/linux/ M=`pwd` clean

.phony : modules clean
