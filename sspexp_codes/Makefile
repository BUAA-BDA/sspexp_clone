INCLUDE = /home/yzengal/icde20/software/sparsehash/include
LIB = /home/yzengal/icde20/software/sparsehash/lib
CXX = g++
CXXFLAGS = -g -w -Wall -Wextra -O3  -std=c++11 -fopenmp -I $(INCLUDE) -L $(LIB)

all: bin bin/sspexp_run

bin/sspexp_run: main.cpp
	$(CXX) $(CXXFLAGS) -Isrc -o $@ $^

bin:
	mkdir -p bin 

clean:
	rm -rf bin
