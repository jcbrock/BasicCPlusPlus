testmakefile: hello.o
	g++ -Wall hello.o -o testmakefile

hello.o: helloworld.cpp
	g++ -Wall -c helloworld.cpp -o hello.o

clean:
	\rm *.o testmakefile
