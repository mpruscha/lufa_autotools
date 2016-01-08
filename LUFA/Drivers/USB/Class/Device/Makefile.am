noinst_LTLIBRARIES = libdevice.la
libdevice_la_SOURCES = AudioClassDevice.c \
											 CDCClassDevice.c \
											 HIDClassDevice.c \
											 MassStorageClassDevice.c \
											 MIDIClassDevice.c \
											 PrinterClassDevice.c \
											 RNDISClassDevice.c


deviceincludedir = $(includedir)/Device

deviceinclude_HEADERS = AudioClassDevice.h \
												CDCClassDevice.h \
												HIDClassDevice.h \
												MassStorageClassDevice.h \
												MIDIClassDevice.h \
												PrinterClassDevice.h \
												RNDISClassDevice.h 


libdevice_la_CPPFLAGS = -I${top_srcdir}/LUFA/ -I${top_srcdir}/LUFA/Drivers/USB/  -I${top_srcdir}/LUFA/Drivers/USB/Class/ -std=c99 
