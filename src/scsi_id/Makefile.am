include $(top_srcdir)/Makefile-globals.am

AM_CPPFLAGS += \
	-DVERSION \
	-I $(top_srcdir)/src/libudev \
	-I $(top_srcdir)/src/udev

udevlibexec_PROGRAMS = \
	scsi_id

scsi_id_SOURCES =\
	scsi_id.c \
	scsi_serial.c \
	scsi.h \
	scsi_id.h

scsi_id_LDADD = \
	$(top_builddir)/src/libudev/libudev-private.la \
	$(top_builddir)/src/udev/libudev-core.la

EXTRA_DIST = \
	README
