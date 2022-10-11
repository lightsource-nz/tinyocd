noinst_LTLIBRARIES += %D%/libocdjtagdrivers.la
%C%_libocdjtagdrivers_la_LIBADD =

%C%_libocdjtagdrivers_la_SOURCES = \
	$(DRIVERFILES) \
	$(DRIVERHEADERS)

%C%_libocdjtagdrivers_la_CPPFLAGS = $(AM_CPPFLAGS)

DRIVERFILES =

# Standard Driver: common files
DRIVERFILES += %D%/driver.c
DRIVERFILES += %D%/jtag_usb_common.c

if USE_LIBUSB1
DRIVERFILES += %D%/libusb_helper.c
%C%_libocdjtagdrivers_la_CPPFLAGS += $(LIBUSB1_CFLAGS)
%C%_libocdjtagdrivers_la_LIBADD += $(LIBUSB1_LIBS)
endif

if PICOPROBE
DRIVERFILES += %D%/picoprobe.c
endif

DRIVERHEADERS = \
	%D%/jtag_usb_common.h \
	%D%/libusb_helper.h \
	%D%/usb_common.h 
