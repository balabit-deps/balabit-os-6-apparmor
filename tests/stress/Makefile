SUBDIRS=subdomain

.PHONY: clean
clean:
	for dir in $(SUBDIRS) ; do \
		make clean -C $${dir} ; \
	done
