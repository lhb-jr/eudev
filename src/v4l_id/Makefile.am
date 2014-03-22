include $(top_srcdir)/Makefile-globals.am

udevlibexec_PROGRAMS = \
	v4l_id

v4l_id_SOURCES = \
	v4l_id.c

v4l_id_LDADD = \
	$(top_builddir)/src/libudev/libudev-private.la \
	$(top_builddir)/src/udev/libudev-core.la
