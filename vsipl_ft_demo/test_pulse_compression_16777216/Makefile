RDIR=..
CC=cc
INCLUDEDIR=-I$(RDIR)/include
LIBDIR=-L$(RDIR)/lib
LIBS=-lvsip -lfftw3f -lm
OPTIONS=-O3

example: test_pulse_compression_16777216.c
	$(CC) -o test_pulse_compression_16777216 test_pulse_compression_16777216.c $(OPTIONS) $(INCLUDEDIR) $(LIBDIR) $(LIBS) 

clean:
	rm -f test_pulse_compression_16777216 test_pulse_compression_16777216.exe
