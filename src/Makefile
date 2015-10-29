CC= gcc

sz_test: canit crctab lsyslog lsz protname rbsb tcp timing zm zperr zreadline
	$(CC) $(CFLAGS) -o sz_test canit.o crctab.o lsyslog.o lsz.o protname.o rbsb.o tcp.o timing.o zm.o zperr.o zreadline.o
	

canit: canit.c
	$(CC) $(CFLAGS) -c canit.c

crctab: crctab.c
	$(CC) $(CFLAGS) -c crctab.c

lsyslog: lsyslog.c
	$(CC) $(CFLAGS) -c lsyslog.c

lsz: lsz.c
	$(CC) $(CFLAGS) -c lsz.c
lrz: lrz.c
	$(CC) $(CFLAGS) -c lrz.c

protname: protname.c
	$(CC) $(CFLAGS) -c protname.c

rbsb: rbsb.c
	$(CC) $(CFLAGS) -c rbsb.c

tcp: tcp.c
	$(CC) $(CFLAGS) -c tcp.c

timing: timing.c
	$(CC) $(CFLAGS) -c timing.c

zm: zm.c
	$(CC) $(CFLAGS) -c zm.c

zperr: zperr.c
	$(CC) $(CFLAGS) -c zperr.c

zreadline: zreadline.c
	$(CC) $(CFLAGS) -c zreadline.c

	

clean:
	rm -rf *.o sz_test


