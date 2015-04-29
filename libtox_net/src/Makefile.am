## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\"

AM_CFLAGS =\
	 -Wall\
	 -g

lib_LTLIBRARIES = libtox_net.la


libtox_net_la_SOURCES = \
	lib.c

libtox_net_la_LDFLAGS = 

libtox_net_la_LIBADD = 


if PLATFORM_WIN32
libtox_net_la_LDFLAGS += -no-undefined
endif

if NATIVE_WIN32
libtox_net_la_LDFLAGS += -export-dynamic
endif

include_HEADERS = \
	libtox_net.h

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libtox_net-0.1.pc

EXTRA_DIST = \
	libtox_net-0.1.pc.in
