opensusebrandingdir = $(datadir)/cockpit/branding/opensuse

opensusebranding_DATA = \
	src/branding/opensuse/branding.css \
	$(NULL)

EXTRA_DIST += $(opensusebranding_DATA)

install-data-hook::
	$(LN_S) -f /usr/share/wallpapers/default-1920x1200.jpg $(DESTDIR)$(opensusebrandingdir)/default-1920x1200.jpg
	$(LN_S) -f /usr/share/pixmaps/distribution-logos/square-hicolor.svg $(DESTDIR)$(opensusebrandingdir)/square-hicolor.svg
