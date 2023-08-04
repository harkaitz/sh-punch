PROJECT=sh-punch
VERSION=1.0.0
DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:

## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/punch            $(DESTDIR)$(PREFIX)/bin
	cp bin/punch-files      $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE README.md $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
update: update-license
update-license:
	ssnip README.md
## -- BLOCK:license --
