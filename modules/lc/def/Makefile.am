AM_CFLAGS= \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/include/X11 \
	-I$(top_builddir)/include \
	-I$(top_builddir)/include/X11 \
	-I$(top_srcdir)/src/xcms \
	-I$(top_srcdir)/src/xkb \
	-I$(top_srcdir)/src/xlibi18n \
	$(X11_CFLAGS) \
	$(BIGREQS_CFLAGS) \
	$(BIGFONT_CFLAGS) \
	$(XDMCP_CFLAGS) \
	-D_BSD_SOURCE

if XLIB_LOADABLE_I18N

commonlibdir = $(X11_LOCALELIBDIR)/common
commonlib_LTLIBRARIES=xlcDef.la
xlcDef_la_LDFLAGS = -module -version-number 2:0:0
xlcDef_la_LIBADD = $(I18N_MODULE_LIBS)

else

noinst_LTLIBRARIES = libxlcDef.la

endif

xlcDef_la_SOURCES = \
	lcDefConv.c

libxlcDef_la_SOURCES = $(xlcDef_la_SOURCES)
