cmake_minimum_required(VERSION 3.6)   # CMake version check
project(TripleRefPointersInC)
set(CMAKE_CXX_STANDARD 11)            # Enable c++11 standard
set(SOURCE_FILES cookout.c cookout.c)
add_executable(cookout ${SOURCE_FILES})