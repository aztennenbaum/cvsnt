## Process this file with automake to produce Makefile.in
# Makefile.am for GNU CVS man pages.
# Copyright (C) 1986-1992, 2000 Free Software Foundation, Inc.

# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2, or (at your option)
# any later version.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.

man_MANS = cvs.1 cvs.5 cvslockd.1 Plugins.5 PServer.5
EXTRA_DIST = \
	.cvsignore \
	$(man_MANS)

# for backwards compatibility with the old makefiles
realclean: maintainer-clean
.PHONY: realclean
