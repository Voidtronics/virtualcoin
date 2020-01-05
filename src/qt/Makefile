.PHONY: FORCE
all: FORCE
	$(MAKE) -C .. virtualcoin_qt test_virtualcoin_qt
clean: FORCE
	$(MAKE) -C .. virtualcoin_qt_clean test_virtualcoin_qt_clean
check: FORCE
	$(MAKE) -C .. test_virtualcoin_qt_check
virtualcoin-qt virtualcoin-qt.exe: FORCE
	 $(MAKE) -C .. virtualcoin_qt
