ACLOCAL_AMFLAGS = -I m4  ${ACLOCAL_FLAGS}

NULL = 

SUBDIRS =								\
	data								\
	x11-clipboard-manager						\
	panel-plugin							\
	tests								\
	po								\
	$(NULL)

distclean-local:
	rm -rf *.cache *~

EXTRA_DIST =								\
	AUTHORS								\
	ChangeLog							\
	COPYING								\
	NEWS								\
	README.md								\
	intltool-extract.in						\
	intltool-merge.in						\
	intltool-update.in						\
	$(NULL)

CLEANFILES =								\
	$(NULL)

DISTCLEANFILES =							\
	aclocal.m4							\
	compile								\
	config.guess							\
	config.h.in							\
	config.sub							\
	configure							\
	configure.ac							\
	depcomp								\
	install-sh							\
	ltmain.sh							\
	missing								\
	mkinstalldirs							\
	intltool-extract						\
	intltool-merge							\
	intltool-update							\
	$(NULL)

# vi:set ts=8 sw=8 noet ai nocindent syntax=automake:
