CC = gcc
CFLAGS = -g -O2 -Wall -I .
LIB = -lpthread -lrt
# This flag includes the Pthreads library on a Linux box.
# Others systems will probably require something different.

echoclient: echoclient.c csapp.o
	$(CC) $(CFLAGS) -o echoclient echoclient.c csapp.o $(LIB)

csapp.o: ../csapp.c ../csapp.h
	$(CC) $(CFLAGS) -c ../csapp.c

clean:
	rm -f *.o echoclient echo *~
