# Makefile for the focaltech touchscreen drivers.

obj-$(CONFIG_TOUCHSCREEN_FOCALTECH_MMI) := focaltech_0flash_mmi.o

focaltech_0flash_mmi-objs	+=  focaltech_core.o
focaltech_0flash_mmi-objs	+=  focaltech_ex_fun.o
focaltech_0flash_mmi-objs	+=  focaltech_ex_mode.o
focaltech_0flash_mmi-objs	+=  focaltech_gesture.o
focaltech_0flash_mmi-objs	+=  focaltech_esdcheck.o
focaltech_0flash_mmi-objs	+=  focaltech_point_report_check.o
focaltech_0flash_mmi-objs   += focaltech_test/focaltech_test.o
focaltech_0flash_mmi-objs   += focaltech_test/focaltech_test_ini.o

focaltech_0flash_mmi-objs += focaltech_test/supported_ic/focaltech_test_ft8756.o
focaltech_0flash_mmi-objs += focaltech_flash_ft8756.o
focaltech_0flash_mmi-objs += focaltech_spi_v1_1_1.o
focaltech_0flash_mmi-objs	+=  focaltech_flash.o

