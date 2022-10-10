noinst_LTLIBRARIES += %D%/libocdusbblaster.la
%C%_libocdusbblaster_la_SOURCES = $(USB_BLASTER_SRC)
%C%_libocdusbblaster_la_CPPFLAGS = -I$(top_srcdir)/src/jtag/drivers $(AM_CPPFLAGS) $(LIBUSB1_CFLAGS)

USB_BLASTER_SRC = %D%/usb_blaster.c %D%/ublast_access.h

if USB_BLASTER_2
USB_BLASTER_SRC += %D%/ublast2_access_libusb.c
endif
