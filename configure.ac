#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.5])
AC_INIT([hfcxx], [1.4.1], [ivo@zuidstijl.nl])
AM_INIT_AUTOMAKE([foreign -Wall -Werror])
AM_PATH_CPPUNIT(1.9.6)
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile src/Makefile tests/Makefile])

# Checks for programs.
AC_PROG_CXX

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h string.h sys/time.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_CHECK_FUNCS([floor gettimeofday pow sqrt])

AC_OUTPUT
