

all: main.o myfunc.o
	g++ -o myexe main.o myfunc.o

myfunc.o: myfunc.cpp myfunc.h
	g++ -c myfunc.cpp

main.o: main.cpp myfunc.h
	g++ -c main.cpp

clean:
	rm -rf *.o myexe myexe1
	