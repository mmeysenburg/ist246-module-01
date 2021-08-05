TestSimpleSLL:	SimpleSLL.o TestSimpleSLL.o
	g++ -std=c++11 -Wall SimpleSLL.o TestSimpleSLL.o -o TestSimpleSLL

SimpleSLL.o:	SimpleSLL.cpp
	g++ -std=c++11 -Wall -c SimpleSLL.cpp

TestSimpleSLL.o:	TestSimpleSLL.cpp
	g++ -std=c++11 -Wall -c TestSimpleSLL.cpp

clean:
	rm *.o TestSimpleSLL
