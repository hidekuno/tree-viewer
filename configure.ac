#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([tree-viewer], [0.12], [hidekuno@gmail.com])

AC_CONFIG_SRCDIR([main.cpp])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CXXCPP
AC_PROG_RANLIB

# Checks for libraries.

# Checks for header files.
AC_LANG_PUSH([C++])
AC_CHECK_HEADERS([google/dense_hash_map], [], AC_MSG_ERROR([Missing google headers.]))
AC_LANG_POP([C++])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T

# Checks for library functions.
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
