ACLOCAL_AMFLAGS = -I m4 ${ACLOCAL_FLAGS}

AUTOMAKE_OPTIONS = foreign

SUBDIRS = ext src

DOCS = \
	AUTHORS			\
	COPYING.LGPLv2.1	\
	$(NULL)

EXTRA_DIST = $(DOCS)

# Extra clean files so that maintainer-clean removes *everything*
MAINTAINERCLEANFILES = \
	aclocal.m4 compile config.guess config.sub \
	configure depcomp install-sh ltmain.sh     \
	Makefile.in missing config.h.in
