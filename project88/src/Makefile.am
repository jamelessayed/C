## Process this file with automake to produce Makefile.in

INCLUDES = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	@PACKAGE_CFLAGS@

bin_PROGRAMS = project7

project7_SOURCES = \
	main.c \
	support.c support.h \
	interface.c interface.h \
	callbacks.c callbacks.h	\
	gestion_election.c gestion_election.h \
	reclamation.c reclamation.h \
	liste.c	liste.h \
	user.c user.h	\
	observateurMG.c observateurMG.h \
	bureau.c bureau.h

project7_LDADD = @PACKAGE_LIBS@ $(INTLLIBS)

