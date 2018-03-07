#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([Lab 2 Sample Solution], [0.1], [brady@cs.tcd.ie])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([pandc.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.

AC_CHECK_LIB([pthread],[pthread_create], , AC_MSG_ERROR(pthread library needed))


# Checks for header files.
AC_CHECK_HEADERS([stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile])

AC_OUTPUT
