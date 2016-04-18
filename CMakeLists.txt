cmake_minimum_required(VERSION 3.5)
project(xor)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp Bp.cpp Bp.h)
add_executable(xor ${SOURCE_FILES})