CC=gcc
CFLAGS=-g0

libvalsrc.so: valsrc.c valsrc.h
	$(CC) -shared -o $@ valsrc.c $(CFLAGS) 

.PHONY: clean

clean:
	rm libvalsrc.so
