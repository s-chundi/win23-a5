calculator: addition.o main.o division.o multiplication.o subtraction.o
	cc -o calculator addition.o main.o division.o multiplication.o subtraction.o

addition.o: addition.c
	cc -c -o addition.o addition.c

main.o: main.c
	cc -c -o main.o main.c

division.o: division.c
	cc -c -o division.o division.c

multiplication.o: multiplication.c
	cc -c -o multiplication.o multiplication.c

subtraction.o: subtraction.c
	cc -c -o subtraction.o subtraction.c

clean:
	rm -f calculator addition.o main.o division.o multiplication.o subtraction.o


