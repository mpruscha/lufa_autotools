AC_INIT(lufa_library, 1.0, me@mail.com)
AC_CONFIG_AUX_DIR(config)

AM_INIT_AUTOMAKE([foreign subdir-objects])
AC_CONFIG_HEADERS([conf.h])


AC_PROG_CC
AC_PROG_CC_STDC
AC_PROG_RANLIB
AM_PROG_AR

LT_INIT

AC_CONFIG_SRCDIR(LUFA/Drivers/Board/Board.h)

AC_OUTPUT([Makefile 
          LUFA/Drivers/USB/Core/Makefile 
          LUFA/Drivers/USB/Core/AVR8/Makefile
          LUFA/Drivers/USB/Class/Device/Makefile
          LUFA/Makefile
          LUFA/Drivers/Makefile
          LUFA/Drivers/USB/Makefile
          LUFA/Platform/Makefile
          LUFA/Common/Makefile
          LUFA/Drivers/USB/Class/Makefile
          LUFA/Drivers/USB/Class/Common/Makefile
          ])
