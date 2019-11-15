CXX_OPT_FLAGS := -O3 -DNDEBUG

EIGEN_INCLUDE ?= $(shell pkg-config --cflags eigen3)

simple_demo: simple_demo.cpp
	g++ -I "$(EIGEN_INCLUDE)" -I../src/ simple_demo.cpp -o simple_demo $(CXX_OPT_FLAGS)

all: simple_demo
