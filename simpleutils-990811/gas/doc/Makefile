# Generated automatically from Makefile.in by configure.
# Makefile.in generated automatically by automake 1.4 from Makefile.am

# Copyright (C) 1994, 1995-8, 1999 Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.


SHELL = /bin/sh

srcdir = .
top_srcdir = ..
prefix = /home/honey/simplescalar
exec_prefix = ${prefix}

bindir = ${exec_prefix}/bin
sbindir = ${exec_prefix}/sbin
libexecdir = ${exec_prefix}/libexec
datadir = ${prefix}/share
sysconfdir = ${prefix}/etc
sharedstatedir = ${prefix}/com
localstatedir = ${prefix}/var
libdir = ${exec_prefix}/lib
infodir = ${prefix}/info
mandir = ${prefix}/man
includedir = ${prefix}/include
oldincludedir = /usr/include

DESTDIR =

pkgdatadir = $(datadir)/gas
pkglibdir = $(libdir)/gas
pkgincludedir = $(includedir)/gas

top_builddir = ..

ACLOCAL = aclocal
AUTOCONF = autoconf
AUTOMAKE = /home/honey/simplescalar/simpleutils-990811/missing automake
AUTOHEADER = /home/honey/simplescalar/simpleutils-990811/missing autoheader

INSTALL = /usr/bin/install -c
INSTALL_PROGRAM = ${INSTALL} $(AM_INSTALL_PROGRAM_FLAGS)
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_SCRIPT = ${INSTALL_PROGRAM}
transform = s,^,sslittle-na-sstrix-,; 

NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_alias = i686-pc-linux
build_triplet = i686-pc-linux-gnu
host_alias = i686-pc-linux
host_triplet = i686-pc-linux-gnu
target_alias = sslittle-na-sstrix
target_triplet = sslittle-na-sstrix
ALL_OBJ_DEPS =  ../bfd/bfd.h
AS = 
BFDLIB = ../bfd/libbfd.la
CATALOGS = 
CATOBJEXT = .gmo
CC = gcc
DATADIRNAME = share
DLLTOOL = 
EXEEXT = 
GDBINIT = .gdbinit
GMOFILES = 
GMSGFMT = no
GT_NO = 
GT_YES = #YES#
INCLUDE_LOCALE_H = #include <locale.h>
INSTOBJEXT = .mo
INTLDEPS = $(top_builddir)/../intl/libintl.a
INTLLIBS = $(top_builddir)/../intl/libintl.a
INTLOBJS = $(GETTOBJS)
LD = /usr/bin/ld
LEX = flex
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
MAINT = #
MAKEINFO = /home/honey/simplescalar/simpleutils-990811/missing makeinfo
MKINSTALLDIRS = $(srcdir)/../../mkinstalldirs
MSGFMT = no
NM = /usr/bin/nm -B
OPCODES_LIB = ../opcodes/libopcodes.la
PACKAGE = gas
POFILES = 
POSUB = po
RANLIB = ranlib
USE_INCLUDED_LIBINTL = yes
USE_NLS = yes
USE_SYMBOL_UNDERSCORE = no
VERSION = 2.9.5
YACC = bison -y
atof = ieee
cgen_cpu_prefix = 
extra_objects = 
install_tooldir = install-exec-tooldir
l = 
obj_format = ecoff
target_cpu_type = ss
te_file = generic

AUTOMAKE_OPTIONS = cygnus

# What version of the manual you want; "all" includes everything
CONFIG = all

man_MANS = as.1

info_TEXINFOS = as.texinfo gasp.texi

CPU_DOCS =  	c-a29k.texi 	c-arm.texi 	c-d10v.texi 	c-h8300.texi 	c-h8500.texi 	c-hppa.texi 	c-i386.texi 	c-i960.texi 	c-m68k.texi 	c-mips.texi 	c-ns32k.texi 	c-sh.texi 	c-sparc.texi 	c-vax.texi 	c-v850.texi 	c-z8k.texi


# This one isn't ready for prime time yet.  Not even a little bit.

noinst_TEXINFOS = internals.texi

DISTCLEANFILES = asconfig.texi

MAINTAINERCLEANFILES = gasver.texi
mkinstalldirs = $(SHELL) $(top_srcdir)/../mkinstalldirs
CONFIG_HEADER = ../config.h
CONFIG_CLEAN_FILES = 
TEXI2DVI = `if test -f $(top_srcdir)/../texinfo/util/texi2dvi; then echo $(top_srcdir)/../texinfo/util/texi2dvi; else echo texi2dvi; fi`
TEXINFO_TEX = $(top_srcdir)/../texinfo/texinfo.tex
INFO_DEPS = as.info gasp.info
DVIS = as.dvi gasp.dvi
TEXINFOS = as.texinfo gasp.texi
man1dir = $(mandir)/man1
MANS = $(man_MANS)

NROFF = nroff
DIST_COMMON =  Makefile.am Makefile.in


DISTFILES = $(DIST_COMMON) $(SOURCES) $(HEADERS) $(TEXINFOS) $(EXTRA_DIST)

TAR = tar
GZIP_ENV = --best
all: all-redirect
.SUFFIXES:
.SUFFIXES: .dvi .info .ps .texi .texinfo .txi
$(srcdir)/Makefile.in: # Makefile.am $(top_srcdir)/configure.in $(ACLOCAL_M4) 
	cd $(top_srcdir) && $(AUTOMAKE) --cygnus doc/Makefile

Makefile: $(srcdir)/Makefile.in  $(top_builddir)/config.status
	cd $(top_builddir) \
	  && CONFIG_FILES=$(subdir)/$@ CONFIG_HEADERS= $(SHELL) ./config.status


as.info: as.texinfo
as.dvi: as.texinfo


gasp.info: gasp.texi
gasp.dvi: gasp.texi


DVIPS = dvips

.texi.info:
	@rm -f $@ $@-[0-9] $@-[0-9][0-9]
	$(MAKEINFO) -I $(srcdir) $<

.texi.dvi:
	TEXINPUTS=$(top_srcdir)/../texinfo/texinfo.tex:$$TEXINPUTS \
	  MAKEINFO='$(MAKEINFO) -I $(srcdir)' $(TEXI2DVI) $<

.texi:
	@rm -f $@ $@-[0-9] $@-[0-9][0-9]
	$(MAKEINFO) -I $(srcdir) $<

.texinfo.info:
	@rm -f $@ $@-[0-9] $@-[0-9][0-9]
	$(MAKEINFO) -I $(srcdir) $<

.texinfo:
	@rm -f $@ $@-[0-9] $@-[0-9][0-9]
	$(MAKEINFO) -I $(srcdir) $<

.texinfo.dvi:
	TEXINPUTS=$(top_srcdir)/../texinfo/texinfo.tex:$$TEXINPUTS \
	  MAKEINFO='$(MAKEINFO) -I $(srcdir)' $(TEXI2DVI) $<

.txi.info:
	@rm -f $@ $@-[0-9] $@-[0-9][0-9]
	$(MAKEINFO) -I $(srcdir) $<

.txi.dvi:
	TEXINPUTS=$(top_srcdir)/../texinfo/texinfo.tex:$$TEXINPUTS \
	  MAKEINFO='$(MAKEINFO) -I $(srcdir)' $(TEXI2DVI) $<

.txi:
	@rm -f $@ $@-[0-9] $@-[0-9][0-9]
	$(MAKEINFO) -I $(srcdir) $<
.dvi.ps:
	$(DVIPS) $< -o $@

install-info-am: $(INFO_DEPS)
	@$(NORMAL_INSTALL)
	$(mkinstalldirs) $(DESTDIR)$(infodir)
	@list='$(INFO_DEPS)'; \
	for file in $$list; do \
	  if test -f $$file; then d=.; else d=$(srcdir); fi; \
	  for ifile in `cd $$d && echo $$file $$file-[0-9] $$file-[0-9][0-9]`; do \
	    if test -f $$d/$$ifile; then \
	      echo " $(INSTALL_DATA) $$d/$$ifile $(DESTDIR)$(infodir)/$$ifile"; \
	      $(INSTALL_DATA) $$d/$$ifile $(DESTDIR)$(infodir)/$$ifile; \
	    else : ; fi; \
	  done; \
	done
	@$(POST_INSTALL)
	@if $(SHELL) -c 'install-info --version | sed 1q | fgrep -s -v -i debian' >/dev/null 2>&1; then \
	  list='$(INFO_DEPS)'; \
	  for file in $$list; do \
	    echo " install-info --info-dir=$(DESTDIR)$(infodir) $(DESTDIR)$(infodir)/$$file";\
	    install-info --info-dir=$(DESTDIR)$(infodir) $(DESTDIR)$(infodir)/$$file || :;\
	  done; \
	else : ; fi

uninstall-info:
	$(PRE_UNINSTALL)
	@if $(SHELL) -c 'install-info --version | sed 1q | fgrep -s -v -i debian' >/dev/null 2>&1; then \
	  ii=yes; \
	else ii=; fi; \
	list='$(INFO_DEPS)'; \
	for file in $$list; do \
	  test -z "$ii" \
	    || install-info --info-dir=$(DESTDIR)$(infodir) --remove $$file; \
	done
	@$(NORMAL_UNINSTALL)
	list='$(INFO_DEPS)'; \
	for file in $$list; do \
	  (cd $(DESTDIR)$(infodir) && rm -f $$file $$file-[0-9] $$file-[0-9][0-9]); \
	done

dist-info: $(INFO_DEPS)
	list='$(INFO_DEPS)'; \
	for base in $$list; do \
	  if test -f $$base; then d=.; else d=$(srcdir); fi; \
	  for file in `cd $$d && eval echo $$base*`; do \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file; \
	  done; \
	done

mostlyclean-aminfo:
	-rm -f as.aux as.cp as.cps as.dvi as.fn as.fns as.ky as.kys as.ps \
	  as.log as.pg as.toc as.tp as.tps as.vr as.vrs as.op as.tr \
	  as.cv as.cn gasp.aux gasp.cp gasp.cps gasp.dvi gasp.fn \
	  gasp.fns gasp.ky gasp.kys gasp.ps gasp.log gasp.pg gasp.toc \
	  gasp.tp gasp.tps gasp.vr gasp.vrs gasp.op gasp.tr gasp.cv \
	  gasp.cn

clean-aminfo:

distclean-aminfo:

maintainer-clean-aminfo:
	for i in $(INFO_DEPS); do \
	  rm -f $$i; \
	  if test "`echo $$i-[0-9]*`" != "$$i-[0-9]*"; then \
	    rm -f $$i-[0-9]*; \
	  fi; \
	done
clean-info: mostlyclean-aminfo

install-man1:
	$(mkinstalldirs) $(DESTDIR)$(man1dir)
	@list='$(man1_MANS)'; \
	l2='$(man_MANS)'; for i in $$l2; do \
	  case "$$i" in \
	    *.1*) list="$$list $$i" ;; \
	  esac; \
	done; \
	for i in $$list; do \
	  if test -f $(srcdir)/$$i; then file=$(srcdir)/$$i; \
	  else file=$$i; fi; \
	  ext=`echo $$i | sed -e 's/^.*\\.//'`; \
	  inst=`echo $$i | sed -e 's/\\.[0-9a-z]*$$//'`; \
	  inst=`echo $$inst | sed '$(transform)'`.$$ext; \
	  echo " $(INSTALL_DATA) $$file $(DESTDIR)$(man1dir)/$$inst"; \
	  $(INSTALL_DATA) $$file $(DESTDIR)$(man1dir)/$$inst; \
	done

uninstall-man1:
	@list='$(man1_MANS)'; \
	l2='$(man_MANS)'; for i in $$l2; do \
	  case "$$i" in \
	    *.1*) list="$$list $$i" ;; \
	  esac; \
	done; \
	for i in $$list; do \
	  ext=`echo $$i | sed -e 's/^.*\\.//'`; \
	  inst=`echo $$i | sed -e 's/\\.[0-9a-z]*$$//'`; \
	  inst=`echo $$inst | sed '$(transform)'`.$$ext; \
	  echo " rm -f $(DESTDIR)$(man1dir)/$$inst"; \
	  rm -f $(DESTDIR)$(man1dir)/$$inst; \
	done
install-man: $(MANS)
	@$(NORMAL_INSTALL)
	$(MAKE) $(AM_MAKEFLAGS) install-man1
uninstall-man:
	@$(NORMAL_UNINSTALL)
	$(MAKE) $(AM_MAKEFLAGS) uninstall-man1
tags: TAGS
TAGS:


distdir = $(top_builddir)/$(PACKAGE)-$(VERSION)/$(subdir)

subdir = doc

distdir: $(DISTFILES)
	@for file in $(DISTFILES); do \
	  if test -f $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    cp -pr $$/$$file $(distdir)/$$file; \
	  else \
	    test -f $(distdir)/$$file \
	    || ln $$d/$$file $(distdir)/$$file 2> /dev/null \
	    || cp -p $$d/$$file $(distdir)/$$file || :; \
	  fi; \
	done
	$(MAKE) $(AM_MAKEFLAGS) top_distdir="$(top_distdir)" distdir="$(distdir)" dist-info
info-am: $(INFO_DEPS)
info: info-am
dvi-am: $(DVIS)
dvi: dvi-am
check-am:
check: check-am
installcheck-am:
installcheck: installcheck-am
install-info-am: 
install-info: install-info-am
install-exec-am:
install-exec: install-exec-am

install-data-am: install-man
install-data: install-data-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
install: install-am
uninstall-am: uninstall-man
uninstall: uninstall-am
all-am: Makefile $(MANS)
all-redirect: all-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) AM_INSTALL_PROGRAM_FLAGS=-s install
installdirs:
	$(mkinstalldirs)  $(DESTDIR)$(mandir)/man1


mostlyclean-generic:

clean-generic:

distclean-generic:
	-rm -f Makefile $(CONFIG_CLEAN_FILES)
	-rm -f config.cache config.log stamp-h stamp-h[0-9]*
	-test -z "$(DISTCLEANFILES)" || rm -f $(DISTCLEANFILES)

maintainer-clean-generic:
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
mostlyclean-am:  mostlyclean-aminfo mostlyclean-generic

mostlyclean: mostlyclean-am

clean-am:  clean-aminfo clean-generic mostlyclean-am

clean: clean-am

distclean-am:  distclean-aminfo distclean-generic clean-am
	-rm -f libtool

distclean: distclean-am

maintainer-clean-am:  maintainer-clean-aminfo maintainer-clean-generic \
		distclean-am
	@echo "This command is intended for maintainers to use;"
	@echo "it deletes files that may require special tools to rebuild."

maintainer-clean: maintainer-clean-am

.PHONY: install-info-am uninstall-info mostlyclean-aminfo \
distclean-aminfo clean-aminfo maintainer-clean-aminfo install-man1 \
uninstall-man1 install-man uninstall-man tags distdir info-am info \
dvi-am dvi check check-am installcheck-am installcheck install-info-am \
install-info install-exec-am install-exec install-data-am install-data \
install-am install uninstall-am uninstall all-redirect all-am all \
installdirs mostlyclean-generic distclean-generic clean-generic \
maintainer-clean-generic clean mostlyclean distclean maintainer-clean


asconfig.texi: $(CONFIG).texi
	rm -f asconfig.texi
	ln -s $(srcdir)/$(CONFIG).texi ./asconfig.texi >/dev/null 2>&1 \
	  || ln $(srcdir)/$(CONFIG).texi ./asconfig.texi >/dev/null 2>&1 \
	  || cp $(srcdir)/$(CONFIG).texi ./asconfig.texi

gasver.texi: Makefile
	rm -f $@
	echo '@set VERSION $(VERSION)' > $@

as.info: $(srcdir)/as.texinfo asconfig.texi gasver.texi $(CPU_DOCS)
as.dvi: $(srcdir)/as.texinfo asconfig.texi gasver.texi $(CPU_DOCS)

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
