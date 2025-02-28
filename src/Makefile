daadmaker drf mcrf: $(wildcard *.pas)
	fpc $@

build: daadmaker drf mcrf

install: build
	install -m755 daadmaker $(DESTDIR)/usr/bin/daadmaker
	install -m755 drf $(DESTDIR)/usr/bin/drf
	install -m755 mcrf $(DESTDIR)/usr/bin/mcrf
