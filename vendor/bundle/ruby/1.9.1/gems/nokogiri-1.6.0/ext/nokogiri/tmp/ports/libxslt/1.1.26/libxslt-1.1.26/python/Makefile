# Makefile.in generated by automake 1.11 from Makefile.am.
# python/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009  Free Software Foundation,
# Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




pkgdatadir = $(datadir)/libxslt
pkgincludedir = $(includedir)/libxslt
pkglibdir = $(libdir)/libxslt
pkglibexecdir = $(libexecdir)/libxslt
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = i686-pc-linux-gnu
host_triplet = i686-pc-linux-gnu
subdir = python
DIST_COMMON = $(srcdir)/Makefile.am $(srcdir)/Makefile.in TODO
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/configure.in
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__installdirs = "$(DESTDIR)$(pythondir)"
LTLIBRARIES = $(python_LTLIBRARIES)
#libxsltmod_la_DEPENDENCIES = $(mylibs)
am__libxsltmod_la_SOURCES_DIST = libxslt.c types.c libxslt-py.c
#am_libxsltmod_la_OBJECTS = libxslt.lo types.lo \
#	libxslt-py.lo
libxsltmod_la_OBJECTS = $(am_libxsltmod_la_OBJECTS)
libxsltmod_la_LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(libxsltmod_la_LDFLAGS) $(LDFLAGS) -o $@
#am_libxsltmod_la_rpath = -rpath $(pythondir)
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
SOURCES = $(libxsltmod_la_SOURCES)
DIST_SOURCES = $(am__libxsltmod_la_SOURCES_DIST)
RECURSIVE_TARGETS = all-recursive check-recursive dvi-recursive \
	html-recursive info-recursive install-data-recursive \
	install-dvi-recursive install-exec-recursive \
	install-html-recursive install-info-recursive \
	install-pdf-recursive install-ps-recursive install-recursive \
	installcheck-recursive installdirs-recursive pdf-recursive \
	ps-recursive uninstall-recursive
RECURSIVE_CLEAN_TARGETS = mostlyclean-recursive clean-recursive	\
  distclean-recursive maintainer-clean-recursive
AM_RECURSIVE_TARGETS = $(RECURSIVE_TARGETS:-recursive=) \
	$(RECURSIVE_CLEAN_TARGETS:-recursive=) tags TAGS ctags CTAGS \
	distdir
ETAGS = etags
CTAGS = ctags
DIST_SUBDIRS = $(SUBDIRS)
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
am__relativize = \
  dir0=`pwd`; \
  sed_first='s,^\([^/]*\)/.*$$,\1,'; \
  sed_rest='s,^[^/]*/*,,'; \
  sed_last='s,^.*/\([^/]*\)$$,\1,'; \
  sed_butlast='s,/*[^/]*$$,,'; \
  while test -n "$$dir1"; do \
    first=`echo "$$dir1" | sed -e "$$sed_first"`; \
    if test "$$first" != "."; then \
      if test "$$first" = ".."; then \
        dir2=`echo "$$dir0" | sed -e "$$sed_last"`/"$$dir2"; \
        dir0=`echo "$$dir0" | sed -e "$$sed_butlast"`; \
      else \
        first2=`echo "$$dir2" | sed -e "$$sed_first"`; \
        if test "$$first2" = "$$first"; then \
          dir2=`echo "$$dir2" | sed -e "$$sed_rest"`; \
        else \
          dir2="../$$dir2"; \
        fi; \
        dir0="$$dir0"/"$$first"; \
      fi; \
    fi; \
    dir1=`echo "$$dir1" | sed -e "$$sed_rest"`; \
  done; \
  reldir="$$dir2"
ACLOCAL = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/missing --run aclocal-1.11
AMTAR = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/missing --run tar
AR = ar
AS = as
AUTOCONF = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/missing --run autoconf
AUTOHEADER = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/missing --run autoheader
AUTOMAKE = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/missing --run automake-1.11
AWK = mawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2 -Wall
CPP = gcc -E
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = dlltool
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
EXSLT_INCLUDEDIR = -I${includedir}
EXSLT_LIBDIR = -L${libdir}
EXSLT_LIBS = -lexslt -lxslt  -L/home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/lib -lxml2 -lz -lm -lm 
EXTRA_LIBS =   -L/home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/lib -lxml2 -lz -lm -lm
FGREP = /bin/grep -F
GREP = /bin/grep
HTML_DIR = $(datadir)/doc/$(PACKAGE)-$(VERSION)/html
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LD = /usr/bin/ld
LDFLAGS = 
LIBEXSLT_MAJOR_VERSION = 0
LIBEXSLT_MICRO_VERSION = 15
LIBEXSLT_MINOR_VERSION = 8
LIBEXSLT_VERSION = 0.8.15
LIBEXSLT_VERSION_EXTRA = 
LIBEXSLT_VERSION_INFO = 8:15:8
LIBEXSLT_VERSION_NUMBER = 815
LIBGCRYPT_CFLAGS = 
LIBGCRYPT_CONFIG = 
LIBGCRYPT_LIBS = 
LIBOBJS = 
LIBS = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIBXML_CFLAGS =  -I/home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/include/libxml2
LIBXML_LIBS =  -L/home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/lib -lxml2 -lz -lm
LIBXML_REQUIRED_VERSION = 2.6.27
LIBXML_SRC = 
LIBXSLT_DEFAULT_PLUGINS_PATH = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxslt/1.1.26/lib/libxslt-plugins
LIBXSLT_MAJOR_MINOR_VERSION = 1.1
LIBXSLT_MAJOR_VERSION = 1
LIBXSLT_MICRO_VERSION = 26
LIBXSLT_MINOR_VERSION = 1
LIBXSLT_VERSION = 1.1.26
LIBXSLT_VERSION_EXTRA = 
LIBXSLT_VERSION_INFO = 2:26:1
LIBXSLT_VERSION_NUMBER = 10126
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAKEINFO = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/missing --run makeinfo
MKDIR_P = /bin/mkdir -p
MV = /bin/mv
M_LIBS = -lm
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = libxslt
PACKAGE_BUGREPORT = 
PACKAGE_NAME = 
PACKAGE_STRING = 
PACKAGE_TARNAME = 
PACKAGE_VERSION = 
PATH_SEPARATOR = :
PERL = perl
PYTHON = 
PYTHONSODV = 
PYTHON_INCLUDES = 
PYTHON_SITE_PACKAGES = 
PYTHON_SUBDIR = 
PYTHON_VERSION = 
RANLIB = ranlib
RELDATE = Sat Sep 28 2013
RM = /bin/rm
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
STATIC_BINARIES = 
STRIP = strip
TAR = /bin/tar
THREAD_LIBS = -lpthread
VERSION = 1.1.26
VERSION_SCRIPT_FLAGS = -Wl,--version-script=
WIN32_EXTRA_LDFLAGS = 
WIN32_EXTRA_LIBADD = 
WITH_CRYPTO = 0
WITH_DEBUGGER = 1
WITH_MEM_DEBUG = 0
WITH_MODULES = 1
WITH_TRIO = 0
WITH_XSLT_DEBUG = 1
XMLLINT = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/bin/xmllint
XML_CONFIG = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/bin/xml2-config
XSLTPROC = /usr/bin/xsltproc
XSLTPROCDV = 
XSLT_INCLUDEDIR = -I${includedir}
XSLT_LIBDIR = -L${libdir}
XSLT_LIBS = -lxslt  -L/home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxml2/2.8.0/lib -lxml2 -lz -lm -lm
XSLT_LOCALE_WINAPI = 0
XSLT_LOCALE_XLOCALE = 1
abs_builddir = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/python
abs_srcdir = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/python
abs_top_builddir = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26
abs_top_srcdir = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26
ac_ct_CC = gcc
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build = i686-pc-linux-gnu
build_alias = 
build_cpu = i686
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = i686-pc-linux-gnu
host_alias = 
host_cpu = i686
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ext/nokogiri/tmp/ports/libxslt/1.1.26/libxslt-1.1.26/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
lt_ECHO = echo
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /home/igawa/repo/proofreadingchecker/vendor/bundle/ruby/1.9.1/gems/nokogiri-1.6.0/ports/libxslt/1.1.26
program_transform_name = s,x,x,
psdir = ${docdir}
pythondir = 
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..

# Makefile for libxml2 python library
AUTOMAKE_OPTIONS = 1.4 foreign
SUBDIRS = . tests
INCLUDES = \
	-I$(PYTHON_INCLUDES) \
	 $(LIBXML_CFLAGS) \
	-I$(top_srcdir)/libxslt \
	-I$(top_srcdir) \
	-I../libexslt

DOCS_DIR = $(datadir)/doc/libxslt-python-$(LIBXSLT_VERSION)
# libxsltclass.txt is generated
DOCS = TODO
EXTRA_DIST = \
	libxslt.c		\
	types.c			\
	generator.py		\
	libxml_wrap.h		\
	libxslt_wrap.h		\
	libxsl.py		\
	libxslt-python-api.xml	\
	$(DOCS)

libxsltmod_la_LDFLAGS = $(WIN32_EXTRA_LDFLAGS) -module -avoid-version
#mylibs = \
#	$(top_builddir)/libxslt/libxslt.la \
#	$(top_builddir)/libexslt/libexslt.la

#python_LTLIBRARIES = libxsltmod.la
#libxsltmod_la_SOURCES = libxslt.c types.c libxslt-py.c
#libxsltmod_la_LIBADD = $(mylibs) 
#GENERATE = generator.py
#API_DESC = $(top_srcdir)/doc/libxslt-api.xml $(srcdir)/libxslt-python-api.xml
#GENERATED = $(srcdir)/libxsltclass.py \
#           $(srcdir)/libxslt-export.c \
#	   $(srcdir)/libxslt-py.c \
#	   $(srcdir)/libxslt-py.h \
#	   $(srcdir)/libxsltclass.txt

CLEANFILES = $(GENERATED) *.o libxslt.so *.pyc libxslt.py gen_prog
all: all-recursive

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign python/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign python/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-pythonLTLIBRARIES: $(python_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	test -z "$(pythondir)" || $(MKDIR_P) "$(DESTDIR)$(pythondir)"
	@list='$(python_LTLIBRARIES)'; test -n "$(pythondir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 '$(DESTDIR)$(pythondir)'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 "$(DESTDIR)$(pythondir)"; \
	}

uninstall-pythonLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(python_LTLIBRARIES)'; test -n "$(pythondir)" || list=; \
	for p in $$list; do \
	  $(am__strip_dir) \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f '$(DESTDIR)$(pythondir)/$$f'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f "$(DESTDIR)$(pythondir)/$$f"; \
	done

clean-pythonLTLIBRARIES:
	-test -z "$(python_LTLIBRARIES)" || rm -f $(python_LTLIBRARIES)
	@list='$(python_LTLIBRARIES)'; for p in $$list; do \
	  dir="`echo $$p | sed -e 's|/[^/]*$$||'`"; \
	  test "$$dir" != "$$p" || dir=.; \
	  echo "rm -f \"$${dir}/so_locations\""; \
	  rm -f "$${dir}/so_locations"; \
	done
libxsltmod.la: $(libxsltmod_la_OBJECTS) $(libxsltmod_la_DEPENDENCIES) 
	$(libxsltmod_la_LINK) $(am_libxsltmod_la_rpath) $(libxsltmod_la_OBJECTS) $(libxsltmod_la_LIBADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/libxslt-py.Plo
include ./$(DEPDIR)/libxslt.Plo
include ./$(DEPDIR)/types.Plo

.c.o:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c $<

.c.obj:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c `$(CYGPATH_W) '$<'`

.c.lo:
	$(LTCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

# This directory's subdirectories are mostly independent; you can cd
# into them and run `make' without going through this Makefile.
# To change the values of `make' variables: instead of editing Makefiles,
# (1) if the variable is set in `config.status', edit `config.status'
#     (which will cause the Makefiles to be regenerated when you run `make');
# (2) otherwise, pass the desired values on the `make' command line.
$(RECURSIVE_TARGETS):
	@failcom='exit 1'; \
	for f in x $$MAKEFLAGS; do \
	  case $$f in \
	    *=* | --[!k]*);; \
	    *k*) failcom='fail=yes';; \
	  esac; \
	done; \
	dot_seen=no; \
	target=`echo $@ | sed s/-recursive//`; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    dot_seen=yes; \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done; \
	if test "$$dot_seen" = "no"; then \
	  $(MAKE) $(AM_MAKEFLAGS) "$$target-am" || exit 1; \
	fi; test -z "$$fail"

$(RECURSIVE_CLEAN_TARGETS):
	@failcom='exit 1'; \
	for f in x $$MAKEFLAGS; do \
	  case $$f in \
	    *=* | --[!k]*);; \
	    *k*) failcom='fail=yes';; \
	  esac; \
	done; \
	dot_seen=no; \
	case "$@" in \
	  distclean-* | maintainer-clean-*) list='$(DIST_SUBDIRS)' ;; \
	  *) list='$(SUBDIRS)' ;; \
	esac; \
	rev=''; for subdir in $$list; do \
	  if test "$$subdir" = "."; then :; else \
	    rev="$$subdir $$rev"; \
	  fi; \
	done; \
	rev="$$rev ."; \
	target=`echo $@ | sed s/-recursive//`; \
	for subdir in $$rev; do \
	  echo "Making $$target in $$subdir"; \
	  if test "$$subdir" = "."; then \
	    local_target="$$target-am"; \
	  else \
	    local_target="$$target"; \
	  fi; \
	  ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) $$local_target) \
	  || eval $$failcom; \
	done && test -z "$$fail"
tags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) tags); \
	done
ctags-recursive:
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  test "$$subdir" = . || ($(am__cd) $$subdir && $(MAKE) $(AM_MAKEFLAGS) ctags); \
	done

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS: tags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	if ($(ETAGS) --etags-include --version) >/dev/null 2>&1; then \
	  include_option=--etags-include; \
	  empty_fix=.; \
	else \
	  include_option=--include; \
	  empty_fix=; \
	fi; \
	list='$(SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test ! -f $$subdir/TAGS || \
	      set "$$@" "$$include_option=$$here/$$subdir/TAGS"; \
	  fi; \
	done; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS: ctags-recursive $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    test -d "$(distdir)/$$subdir" \
	    || $(MKDIR_P) "$(distdir)/$$subdir" \
	    || exit 1; \
	  fi; \
	done
	@list='$(DIST_SUBDIRS)'; for subdir in $$list; do \
	  if test "$$subdir" = .; then :; else \
	    dir1=$$subdir; dir2="$(distdir)/$$subdir"; \
	    $(am__relativize); \
	    new_distdir=$$reldir; \
	    dir1=$$subdir; dir2="$(top_distdir)"; \
	    $(am__relativize); \
	    new_top_distdir=$$reldir; \
	    echo " (cd $$subdir && $(MAKE) $(AM_MAKEFLAGS) top_distdir="$$new_top_distdir" distdir="$$new_distdir" \\"; \
	    echo "     am__remove_distdir=: am__skip_length_check=: am__skip_mode_fix=: distdir)"; \
	    ($(am__cd) $$subdir && \
	      $(MAKE) $(AM_MAKEFLAGS) \
	        top_distdir="$$new_top_distdir" \
	        distdir="$$new_distdir" \
		am__remove_distdir=: \
		am__skip_length_check=: \
		am__skip_mode_fix=: \
	        distdir) \
	      || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-recursive
all-local:
all-am: Makefile $(LTLIBRARIES) all-local
installdirs: installdirs-recursive
installdirs-am:
	for dir in "$(DESTDIR)$(pythondir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-recursive
install-exec: install-exec-recursive
install-data: install-data-recursive
uninstall: uninstall-recursive

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-recursive
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
install-data-local:
clean: clean-recursive

clean-am: clean-generic clean-libtool clean-pythonLTLIBRARIES \
	mostlyclean-am

distclean: distclean-recursive
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-recursive

dvi-am:

html: html-recursive

html-am:

info: info-recursive

info-am:

install-data-am: install-data-local install-pythonLTLIBRARIES

install-dvi: install-dvi-recursive

install-dvi-am:

install-exec-am:

install-html: install-html-recursive

install-html-am:

install-info: install-info-recursive

install-info-am:

install-man:

install-pdf: install-pdf-recursive

install-pdf-am:

install-ps: install-ps-recursive

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-recursive
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-recursive

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-recursive

pdf-am:

ps: ps-recursive

ps-am:

uninstall-am: uninstall-pythonLTLIBRARIES

.MAKE: $(RECURSIVE_CLEAN_TARGETS) $(RECURSIVE_TARGETS) ctags-recursive \
	install-am install-strip tags-recursive

.PHONY: $(RECURSIVE_CLEAN_TARGETS) $(RECURSIVE_TARGETS) CTAGS GTAGS \
	all all-am all-local check check-am clean clean-generic \
	clean-libtool clean-pythonLTLIBRARIES ctags ctags-recursive \
	distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-data-local install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am \
	install-pythonLTLIBRARIES install-strip installcheck \
	installcheck-am installdirs installdirs-am maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags tags-recursive uninstall uninstall-am \
	uninstall-pythonLTLIBRARIES


#all-local: libxslt.py

#libxslt.py: $(srcdir)/libxsl.py $(srcdir)/libxsltclass.py
#	cat $(srcdir)/libxsl.py $(srcdir)/libxsltclass.py > libxslt.py

#install-data-local:
#	$(mkinstalldirs) $(DESTDIR)$(pythondir)
#	/usr/bin/install -c -m 0644 libxslt.py $(DESTDIR)$(pythondir)
#	$(mkinstalldirs) $(DESTDIR)$(DOCS_DIR)
#	@(for doc in $(DOCS) ; \
#	   do /usr/bin/install -c -m 0644 $(srcdir)/$$doc $(DESTDIR)$(DOCS_DIR) ; done)

#$(GENERATED): gen_prog

#gen_prog:  $(srcdir)/$(GENERATE) $(API_DESC)
#	cd $(srcdir) && $(PYTHON) $(GENERATE)
#	touch gen_prog

#$(libxsltmod_la_OBJECTS): $(GENERATED)

all: 
tests test: all
	cd tests && $(MAKE) tests

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
