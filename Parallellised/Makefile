CC = icc
CFLAGS = -Ofast -restrict -xavx -qopenmp -Wall -std=c99
LDFLAGS = -lm

jacobi: jacobi.c
	$(CC) $(CFLAGS) -o jacobi jacobi.c $(LDFLAGS)
