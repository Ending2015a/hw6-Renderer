CXX = g++
LDFLAGS = -lm
CXXFLAGS = -O3 -std=c++11 -I./../lodepng -I./../cmdline
TARGETS = hw6_sampler
SOURCES = ../lodepng/lodepng.cpp

.PHONY: all
all: $(TARGETS)

%: main.cpp
	$(CXX) $(CXXFLAGS) $(LDFLAGS) -o $@ $< $(SOURCES)

.PHONY: clean
clean:
	rm -rf $(TARGETS)
