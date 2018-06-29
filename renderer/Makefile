CXX = g++
LDFLAGS = -lm -fopenmp
CXXFLAGS = -O3 -std=c++11 -I./../lodepng -I./../cmdline
TARGETS = hw6_renderer
SOURCES = ../lodepng/lodepng.cpp

.PHONY: all
all: $(TARGETS)

%: main.cpp
	$(CXX) $(LDFLAGS) $(CXXFLAGS) -o $@ $< $(SOURCES)

.PHONY: clean
clean:
	rm -rf $(TARGETS)
