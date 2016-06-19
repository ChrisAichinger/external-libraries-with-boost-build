
all: square.h libsquare.a

square.h:
	echo "int square(int x);" > square.h

libsquare.a: square.o
	ar rcs $@ $^

clean:
	rm -f square.h *.a *.o
