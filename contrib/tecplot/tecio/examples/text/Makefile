# Set to appropriate C++ compiler
CPP=g++
CPPFLAGS=-I../../tecsrc ../../libtecio.a
EXECUTABLE=text
FILES=$(EXECUTABLE).cpp

build:
	$(CPP) $(FILES) $(CPPFLAGS) -o $(EXECUTABLE)

clean:
	rm -f $(EXECUTABLE)
