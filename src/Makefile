TARGETS = 	../bin/Q1/q1a ../bin/Q1/q1b \
			../bin/Q2/q2a ../bin/Q2/q2b ../bin/Q2/q2c ../bin/Q2/q2d ../bin/Q2/q2e \
			../bin/Q3/q3a ../bin/Q3/q3b \
			../bin/Q4/q4a ../bin/Q4/q4b

CC = cc
CFLAGS = -Wall -Wextra -Werror

all: $(TARGETS)

../bin/Q1/q1a: ../bin/Q1 ../Q1/a.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q1/a.c pagerank_alice.c -o ../bin/Q1/q1a

../bin/Q1/q1b: ../bin/Q1 ../Q1/b.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q1/b.c pagerank_alice.c -o ../bin/Q1/q1b

../bin/Q2/q2a: ../bin/Q2 ../Q2/a.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q2/a.c pagerank_alice.c -o ../bin/Q2/q2a

../bin/Q2/q2b: ../bin/Q2 ../Q2/b.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q2/b.c pagerank_alice.c -o ../bin/Q2/q2b

../bin/Q2/q2c: ../bin/Q2 ../Q2/c.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q2/c.c pagerank_alice.c -o ../bin/Q2/q2c

../bin/Q2/q2d: ../bin/Q2 ../Q2/d.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q2/d.c pagerank_alice.c -o ../bin/Q2/q2d

../bin/Q2/q2e: ../bin/Q2 ../Q2/e.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q2/e.c pagerank_alice.c -o ../bin/Q2/q2e

../bin/Q3/q3a: ../bin/Q3 ../Q3/a.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q3/a.c pagerank_alice.c -o ../bin/Q3/q3a

../bin/Q3/q3b: ../bin/Q3 ../Q3/b.c pagerankdumping_bob.c
	$(CC) $(CFLAGS) ../Q3/b.c pagerankdumping_bob.c -o ../bin/Q3/q3b

../bin/Q4/q4a: ../bin/Q4 ../Q4/a.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q4/a.c pagerank_alice.c -o ../bin/Q4/q4a

../bin/Q4/q4b: ../bin/Q4 ../Q4/b.c pagerank_alice.c
	$(CC) $(CFLAGS) ../Q4/b.c pagerank_alice.c -o ../bin/Q4/q4b

../bin/Q1:
	mkdir -p ../bin/Q1/

../bin/Q2:
	mkdir -p ../bin/Q2/

../bin/Q3:
	mkdir -p ../bin/Q3/

../bin/Q4:
	mkdir -p ../bin/Q4/

clean:
	rm -rf ../bin/

re: clean all

.PHONY: all clean