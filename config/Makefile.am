## Process this file with automake to create Makefile.in -*-Makefile-*-

## Makefile for Autoconf.
## Copyright 2001, 2002 Free Software Foundation, Inc.

## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 2, or (at your option)
## any later version.

## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.

## You should have received a copy of the GNU General Public License
## along with this program; if not, write to the Free Software
## Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA
## 02110-1301, USA.

# This line added to force a rebuild of Makefile.in.

EXTRA_DIST = $(SPECIFIC_MACROS) $(SPECIFIC_TOOLS) \
	      prev-version.txt
MAINTAINERCLEANFILES = $(GENERIC_TOOLS)

SPECIFIC_MACROS =				\
m4.m4

GENERIC_TOOLS =					\
config.guess					\
config.sub					\
emacs-comp					\
install-sh					\
mdate-sh					\
missing						\
mkinstalldirs					\
texinfo.tex

SPECIFIC_TOOLS = move-if-change
