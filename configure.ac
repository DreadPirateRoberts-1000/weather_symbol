AC_PREREQ(2.68)
AC_INIT(libweather-symbol, 0.5.1, [post@met.no])
AM_INIT_AUTOMAKE(foreign -Wall -Werror subdir-objects)

AM_PROG_AR
AC_PROG_LIBTOOL
AC_PROG_CXX
AC_CONFIG_MACRO_DIR([m4])

AX_CXX_COMPILE_STDCXX([11])
AX_BOOST_BASE

GMOCK_DIST_CHECK([.])



# Configuration Files
AC_CONFIG_FILES([Makefile libweather-symbol.pc])
AC_OUTPUT
