AC_INIT([homed], [0.1])
AM_INIT_AUTOMAKE([foreign nostdinc subdir-objects -Wall])

AC_CONFIG_HEADERS([src/homed/config.h])

AC_PROG_CC
AM_PROG_VALAC([0.48])

AM_PATH_GLIB_2_0([2.64.0], [], [], [gobject])

AC_CONFIG_FILES([
	src/homed/Makefile
	src/Makefile
	Makefile
])

AC_OUTPUT
