all: stability timing

CC = gcc
CFLAGS = -std=gnu99 -g -Wall -O3 
LDLIBS = -lm

stability: stability.c ../src/tswdft2d.c swdft2d.c swfft2d.c ../src/utils.c ../src/tswdft2d.h
	$(CC) $(CFLAGS) -o stability stability.c ../src/tswdft2d.c swdft2d.c swfft2d.c ../src/utils.c $(LDLIBS)

timing: timing.c ../src/tswdft2d.c swdft2d.c swfft2d.c ../src/utils.c ../src/tswdft2d.h
	$(CC) $(CFLAGS) -o timing timing.c ../src/tswdft2d.c swdft2d.c swfft2d.c ../src/utils.c $(LDLIBS)

clean: 
	rm stability timing
