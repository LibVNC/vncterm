dnl Process this file with autoconf to produce a configure script.

# init
AC_INIT(vncterm, 0.9.10)
AM_INIT_AUTOMAKE

# if this macro is defined, use it
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

# Checks for libraries.
PKG_CHECK_MODULES(LIBVNCSERVER, libvncserver >= 0.9.8)

# Checks for programs.
AC_PROG_CC

AC_OUTPUT([
Makefile
])
