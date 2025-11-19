#
# Makefile for sec_ts touch driver
#

obj-$(CONFIG_TOUCHSCREEN_SEC_TS)   += sec_ts.o
sec_ts-y   += sec_cmd.o sec_ts_fn.o sec_ts_fw.o sec_ts_interface.o sec_ts_only_vendor.o

ccflags-y += -DTOUCH_DRIVER_NOT_SOD_PROXIMITY=1
