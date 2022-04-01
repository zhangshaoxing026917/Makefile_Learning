hello_makefile : hellomakefile.o
	cc  -o hello_makefile hellomakefile.o

hellomakefile.o : hellomakefile.c
	cc -c hellomakefile.c

clean:
	rm hello_makefile *.o

	