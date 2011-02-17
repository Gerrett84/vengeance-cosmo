#
# Makefile for TI's shared transport line discipline
# and its protocol drivers (BT, FM, GPS)
#
obj-$(CONFIG_ST_FM) 		+= fm_drv.o
#fm_drv-objs     		:= fmdrv_common.o fmdrv_rx.o fmdrv_v4l2.o
fm_drv-objs     := fmdrv_core.o fmdrv_v4l2.o fmdrv_st.o fmdrv_mixer.o fmdrv_chr.o
obj-$(CONFIG_TI_ST_GPS)		+= gps_drv.o
