all:
	gcc -Wall ../test/*.c ../test/framework/*.c lib/*.c huffman/*.c main.c -o program -lm

clean:
	rm -rf program
	rm -rf *.exe
	rm -rf *.o

s:
	./program

a:
	make
	./program