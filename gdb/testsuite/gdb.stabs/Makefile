VPATH = ../../.././gdb/testsuite/gdb.stabs
srcdir = ../../.././gdb/testsuite/gdb.stabs

all: 
	@echo "Nothing to be done for all..."

#### host, target, and site specific Makefile frags come in here.

clean mostlyclean:
	-rm -f *.o *~ core tmp.c tmp.s weird.s errs

distclean maintainer-clean realclean: clean
	-rm -f Makefile config.status config.log

Makefile: $(srcdir)/Makefile.in $(srcdir)/configure.ac
	$(SHELL) ./config.status --recheck
