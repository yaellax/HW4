cmake_minimum_required(VERSION 3.15)
project(untitled9)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS -pthread)

add_executable(untitled9 main.cpp boot.cpp boot.h)