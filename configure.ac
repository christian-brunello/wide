#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([WIDE], [0.1.0], [])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([doc/gnu-fdl.texi])

# Checks for programs.
AC_CHECK_PROG([wide_have_makeinfo], [makeinfo], [yes], [no])
AM_CONDITIONAL([BUILD_TEXINFO], [test "x$wide_have_makeinfo" = "xyes"])

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile doc/Makefile])

AC_OUTPUT
