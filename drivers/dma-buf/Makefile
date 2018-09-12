subdir-ccflags-y := -Os -O3
ccflags-y += $(call cc-option,-funroll-loops,-Ofast -fforce-addr ,-finline-functions,-ffast-math )
obj-y := dma-buf.o fence.o reservation.o seqno-fence.o
