DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	@mkdir -p $(DESTDIR)$(PREFIX)/bin
	@echo 'I bin/punch'     ; cp bin/punch       $(DESTDIR)$(PREFIX)/bin
	@echo 'I bin/punch-files'; cp bin/punch-files $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	@echo 'I share/doc/sh-punch/LICENSE'
	@mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-punch
	@cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-punch
## -- license --
