noinst_LTLIBRARIES += %D%/libjtag.la

JTAG_SRCS = %D%/commands.c
%C%_libjtag_la_LIBADD =

include %D%/drivers/Makefile.am
%C%_libjtag_la_LIBADD += $(top_builddir)/%D%/drivers/libocdjtagdrivers.la

%C%_libjtag_la_SOURCES = \
	%D%/adapter.c \
	%D%/core.c \
	%D%/interface.c \
	%D%/interfaces.c \
	%D%/tcl.c \
	%D%/commands.h \
	%D%/driver.h \
	%D%/interface.h \
	%D%/interfaces.h \
	%D%/jtag.h \
	%D%/swd.h \
	%D%/tcl.h \
	$(JTAG_SRCS)

STARTUP_TCL_SRCS += %D%/startup.tcl
