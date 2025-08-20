cmake_minimum_required(VERSION 4.0)
project(test_cpp_DataStructure)

set(CMAKE_CXX_STANDARD 26)

add_executable(
        test_cpp_DataStructure
        main.cpp
        src/list.cpp
        include/list.h
        include/Chapter-2.h
        src/Chapter-2.cpp)
