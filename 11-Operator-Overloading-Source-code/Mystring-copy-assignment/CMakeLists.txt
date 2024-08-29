cmake_minimum_required(VERSION 3.24)
project(Mystring_copy_assignment)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Mystring_copy_assignment
        main.cpp
        Mystring.cpp
        Mystring.h)
