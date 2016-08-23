#
# Makefile for the Imagis touch driver
#
ccflags-y := -Ofast -ffast-math \
             -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr \
             -fsingle-precision-constant -marm -mfpu=neon-vfpv4

# Each configuration option enables a list of files.

obj-$(CONFIG_TOUCHSCREEN_ZINITIX_BT541) +=  zinitix_bt541_ts.o
