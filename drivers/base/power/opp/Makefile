CFLAGS_core.o := -Wno-deprecated-declarations
ccflags-$(CONFIG_DEBUG_DRIVER)	:= -DDEBUG
obj-y				+= core.o cpu.o
obj-$(CONFIG_DEBUG_FS)		+= debugfs.o
