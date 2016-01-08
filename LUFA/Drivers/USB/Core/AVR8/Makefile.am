noinst_LTLIBRARIES = libavr8.la
libavr8_la_SOURCES = Device_AVR8.c \
										 Endpoint_AVR8.c \
										 EndpointStream_AVR8.c \
										 Host_AVR8.c \
										 Pipe_AVR8.c \
										 PipeStream_AVR8.c \
										 USBController_AVR8.c \
										 USBInterrupt_AVR8.c

avr8includedir = $(includedir)/AVR8

avr8include_HEADERS = Device_AVR8.h \
											Endpoint_AVR8.h \
											EndpointStream_AVR8.h \
											Host_AVR8.h \
											OTG_AVR8.h \
											Pipe_AVR8.h \
											PipeStream_AVR8.h \
											USBController_AVR8.h \
											USBInterrupt_AVR8.h


libavr8_la_CPPFLAGS = -I$(top_srcdir)/LUFA/ -I$(top_srcdir)/LUFA/Drivers/USB/ -std=c99 
