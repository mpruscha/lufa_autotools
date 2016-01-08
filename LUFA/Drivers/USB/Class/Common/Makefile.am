noinst_LTLIBRARIES = libclasscommon.la
libclasscommon_la_SOURCES = HIDParser.c 


classcommonincludedir = $(includedir)/Common

classcommoninclude_HEADERS  = AndroidAccessoryClassCommon.h \
															AudioClassCommon.h \
															CDCClassCommon.h \
															HIDClassCommon.h \
															HIDParser.h \
															HIDReportData.h \
															MassStorageClassCommon.h \
															MIDIClassCommon.h \
															PrinterClassCommon.h \
															RNDISClassCommon.h \
															StillImageClassCommon.h


libclasscommon_la_CPPFLAGS = -I${top_srcdir}/LUFA/ -I${top_srcdir}/LUFA/Drivers/USB/  -I${top_srcdir}/LUFA/Drivers/USB/Class/ -std=c99 
