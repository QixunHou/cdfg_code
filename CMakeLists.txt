cmake_minimum_required(VERSION 3.5)
project(Genetic)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES Src/main.cpp Src/CliqueFinder.cpp Headers/CliqueFinder.h Src/Organism.cpp Headers/Organism.h Src/Graph.cpp Headers/Graph.h Src/Vertex.cpp Headers/Vertex.h)

add_executable(Genetic ${SOURCE_FILES})