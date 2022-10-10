noinst_LTLIBRARIES += %D%/librtos.la
%C%_librtos_la_SOURCES = \
	%D%/rtos.c \
	%D%/rtos_standard_stackings.c \
	%D%/hwthread.c \
	%D%/rtos.h \
	%D%/rtos_standard_stackings.h 

%C%_librtos_la_CFLAGS = $(AM_CFLAGS)

if IS_MINGW
# FD_* macros are sloppy with their signs on MinGW32 platform
%C%_librtos_la_CFLAGS += -Wno-sign-compare
endif
