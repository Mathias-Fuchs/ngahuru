# /*
#  *  Ngahuru - GTK+ based simple text editor
#  *  Copyright (C) 2013 Mathias Fuchs
#  *  
#  *  This program is free software; you can redistribute it and/or modify
#  *  it under the terms of the GNU General Public License as published by
#  *  the Free Software Foundation; either version 2 of the License, or
#  *  (at your option) any later version.
#  *  
#  *  This program is distributed in the hope that it will be useful,
#  *  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  *  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  *  GNU General Public License for more details.
#  *  
#  *  You should have received a copy of the GNU General Public License
#  *  along with this program; if not, write to the Free Software
#  *  Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
#  */



bin_PROGRAMS = ngahuru

INCLUDES = -DICONDIR=\"$(datadir)/pixmaps\"

ngahuru_SOURCES = \
	ngahuru.h main.c \
	window.h window.c \
	menu.h menu.c \
	callback.h callback.c \
	view.h view.c \
	undo.h undo.c \
	font.h font.c \
	linenum.h linenum.c \
	indent.h indent.c \
	hlight.h hlight.c \
	selector.h selector.c \
	file.h file.c \
	encoding.h encoding.c \
	search.h search.c \
	dialog.h dialog.c \
	gtkprint.h gtkprint.c \
	gnomeprint.h gnomeprint.c \
	about.h about.c \
	dnd.h dnd.c \
	utils.h utils.c \
	emacs.h emacs.c \
	gtksourceiter.h gtksourceiter.c \
	i18n.h

ngahuru_CFLAGS  = $(GTKSOURCEVIEW_CFLAGS) $(GTK_CFLAGS) $(GNOMEPRINT_CFLAGS)
ngahuru_LDADD   = $(GTKSOURCEVIEW_LIBS) $(GTK_LIBS) $(INTLLIBS) $(GNOMEPRINT_LIBS)
