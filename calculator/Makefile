CC = gcc
CFLAGS = -Wall -Werror

OBJS = main.o addition.o subtraction.o multiplication.o division.o

calculator: $(OBJS)
	$(CC) $(CFLAGS) -o calculator $(OBJS)

main.o: main.c operations.h
	$(CC) $(CFLAGS) -c main.c

subtraction.o: subtraction.c operations.h
	$(CC) $(CFLAGS) -c subtraction.c

addition.o: addition.c operations.h
	$(CC) $(CFLAGS) -c addition.c

division.o: division.c operations.h
	$(CC) $(CFLAGS) -c division.c

multiplication.o: multiplication.c operations.h
	$(CC) $(CFLAGS) -c multiplication.c

clean:
	rm -f *.o calculator
