all: srss

srss: srss.o
	$(CC) -o srss -s srss.o -lm

srss.o: srss.c
	$(CC) -o srss.o -Wall -W -O2 -c srss.c

clean:
	rm srss.o srss
