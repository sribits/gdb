VPATH = ../../.././gdb/testsuite/gdb.asm
srcdir = ../../.././gdb/testsuite/gdb.asm

EXECUTABLES =
MISCELLANEOUS = arch.inc

all info install-info dvi install uninstall installcheck check:
	@echo "Nothing to be done for $@..."

clean mostlyclean:
	-rm -f *~ *.o a.out *.x *.ci *.tmp
	-rm -f core core.coremaker coremaker.core corefile $(EXECUTABLES)
	-rm -f $(MISCELLANEOUS)

distclean maintainer-clean realclean: clean
	-rm -f *~ core
	-rm -f Makefile config.status config.log
	-rm -f *-init.exp
	-rm -fr *.log summary detail *.plog *.sum *.psum site.*
