
build:
	gcc -Wall -g -o test test.c

run: 
	./test input.sample

run_gdb:
	gdb -q -x detect.gdb test

clean_crash:
	rm -rf crash* test.sample

clean_all:
	rm -rf crash* *.o test test.sample peda-session-test.txt