all: srss

srss: srss.o
	gcc -o srss -s srss.o -lm

srss.o: srss.c
	gcc -o srss.o -Wall -W -O2 -c srss.c

clean:
	rm srss.o srss
