
SUBDIRS = \
					LUFA/Common \
          LUFA/Drivers/USB/Core \
					LUFA/Drivers/USB/Core/AVR8 \
					LUFA/Drivers/USB/Class/Device \
					LUFA/Drivers \
					LUFA/Drivers/USB \
					LUFA/Platform



lib_LTLIBRARIES = liblufa.la

liblufa_la_SOURCES = 
liblufa_la_LIBADD = LUFA/Drivers/USB/Core/AVR8/libavr8.la \
									  LUFA/Drivers/USB/Core/libcore.la \
                    LUFA/Drivers/USB/Class/Device/libdevice.la

