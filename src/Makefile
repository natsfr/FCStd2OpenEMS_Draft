all: test

test: test.cpp test.hpp libparsefcstd.so
	g++ test.cpp -o build/test -L./build/ -lparsefcstd

libparsefcstd.so: libparsefcstd.cpp libparsefcstd.hpp
	g++ -Wall -shared -fPIC -lxerces-c -o build/libparsefcstd.so libparsefcstd.cpp
