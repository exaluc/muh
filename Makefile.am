## $Id: Makefile.am,v 1.2 2002/03/24 09:40:18 sebk Exp $

EXTRA_DIST = VERSION
SUBDIRS = src doc misc
ac_local = @ac_local@

install-data-hook:
	@if test $(ac_local) = yes; then \
	    echo "============================================="; \
	    echo "edit $(HOME)/.muh/muhrc !"; \
	    echo "additionally a $(HOME)/muh/-dir has been"; \
	    echo "created and the muh-binary, documentation and"; \
	    echo "some other stuff has been put there!"; \
	    echo "============================================="; \
	fi
