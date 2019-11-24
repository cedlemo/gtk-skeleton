AC_INIT([MyProject], 2.0)
AM_INIT_AUTOMAKE
AC_PROG_CC
PKG_CHECK_MODULES([DEPS], [gtk+-3.0])
PKG_CHECK_MODULES([DEV_DEPS], [gtk+-3.0 cmocka])
AC_CONFIG_FILES([
		 Makefile
		 src/Makefile
		 test/Makefile
		 ])
AC_OUTPUT
