cmake_minimum_required(VERSION 3.17)
project(supercomp_matphis)

set(CMAKE_CXX_STANDARD 14)

set(sources Grid2d.cpp BlockGrid2d.cpp BlockContainer.cpp AlgoVariables.cpp)

add_executable(supercomp_matphis main.cpp)
add_executable(block block.cpp ${sources})