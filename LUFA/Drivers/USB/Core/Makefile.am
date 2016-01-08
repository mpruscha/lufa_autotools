noinst_LTLIBRARIES = libcore.la
libcore_la_SOURCES = ConfigDescriptors.c \
										 DeviceStandardReq.c \
										 Events.c \
										 HostStandardReq.c \
										 USBTask.c

coreincludedir = $(includedir)/Core

coreinclude_HEADERS = USBTask.h \
									USBMode.h \
									Events.h \
									StdDescriptors.h \
									StdRequestType.h \
									ConfigDescriptors.h \
									USBController.h \
									USBInterrupt.h \
									Host.h \
									Pipe.h \
									HostStandardReq.h \
									PipeStream.h \
									Device.h \
									Endpoint.h \
									DeviceStandardReq.h \
									EndpointStream.h \
									OTG.h

libcore_la_CPPFLAGS = -I$(top_srcdir)/LUFA/ -I$(top_srcdir)/LUFA/Drivers/USB/ -I$(top_srcdir)/LUFA/Drivers/USB/Core/ -std=c99 
