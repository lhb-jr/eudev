## Process this file with automake to produce Makefile.in

SUBDIRS = \
	src/libudev \
	src/udev \
	src/accelerometer \
	src/collect \
	src/gudev \
	src/mtd_probe \
	src/ata_id \
	src/cdrom_id \
	src/scsi_id \
	src/v4l_id \
	rules \
	hwdb \
	docs \
	test

if ENABLE_MANPAGES
SUBDIRS += \
	man
endif

if ENABLE_RULE_GENERATOR
SUBDIRS += \
	rule_generator
endif

DISTCHECK_CONFIGURE_FLAGS=--enable-gtk-doc
