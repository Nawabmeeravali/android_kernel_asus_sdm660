#
# Makefile for the kernel auxiliary displays device drivers.
#
subdir-ccflags-y := -Os -O3
ccflags-y += $(call cc-option,-funroll-loops,-Ofast -fforce-addr ,-finline-functions,-ffast-math )

obj-$(CONFIG_KS0108)		+= ks0108.o
obj-$(CONFIG_CFAG12864B)	+= cfag12864b.o cfag12864bfb.o
