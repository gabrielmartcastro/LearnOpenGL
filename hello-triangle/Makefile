CXX := g++

TARGET := app

SRC := $(wildcard src/*.cpp) src/glad.c

CXXFLAGS := -std=c++17 -Wall -Wextra -Iinclude
LDFLAGS := -lglfw -lGL

all:
	$(CXX) $(SRC) $(CXXFLAGS) -o $(TARGET) $(LDFLAGS)

run: all
	./$(TARGET)

clean:
	rm -f $(TARGET)

.PHONY: all run clean
