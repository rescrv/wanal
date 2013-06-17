#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.61])
AC_INIT([no_dist], [0.4.dev], [robert@hyperdex.org])
AM_INIT_AUTOMAKE([foreign subdir-objects dist-bzip2])
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])
AC_CONFIG_SRCDIR([m4/anal_warnings.m4])
AC_CONFIG_MACRO_DIR([m4])

AC_PROG_CXX
AC_PROG_CC

ANAL_WARNINGS

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
