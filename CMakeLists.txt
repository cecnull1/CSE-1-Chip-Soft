cmake_minimum_required(VERSION 4.3)
project(libcse1)

set(CMAKE_CXX_STANDARD 26)

add_library(libcse1 SHARED library.cpp
        cse1/cse1.cpp
        cse1/utils.cpp)
