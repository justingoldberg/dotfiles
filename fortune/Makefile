TARGETS = \
	jargon.dat

all: $(TARGETS)

clean:
	$(RM) $(TARGETS)

%.dat: %
	strfile $<

.PHONY: all clean
