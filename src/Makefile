all: driver2d 

CC = gcc
CFLAGS = -std=gnu99 -g -Wall -O3
LDLIBS = -lm 

driver2d: driver2d.c tswdft2d.c utils.c tswdft2d.h
	$(CC) $(CFLAGS) -o driver2d driver2d.c tswdft2d.c utils.c $(LDLIBS)

clean: 
	rm driver2d
