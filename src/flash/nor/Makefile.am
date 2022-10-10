noinst_LTLIBRARIES += %D%/libocdflashnor.la
%C%_libocdflashnor_la_SOURCES = \
	%D%/core.c \
	%D%/tcl.c \
	$(NOR_DRIVERS) \
	%D%/drivers.c \
	$(NORHEADERS)

NOR_DRIVERS = \
	%D%/jtagspi.c \
	%D%/rp2040.c \
	%D%/spi.c \
	%D%/virtual.c 

NORHEADERS = \
	%D%/core.h \
	%D%/driver.h \
	%D%/imp.h \
	%D%/spi.h 