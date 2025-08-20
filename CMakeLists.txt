cmake_minimum_required(VERSION 4.0)
project(test_cpp_DataStructure)

set(CMAKE_CXX_STANDARD 26)

add_executable(
        test_cpp_DataStructure
        main.cpp
        src/list.cpp
        include/list.h
        include/chapter-2.h
        src/chapter-2.cpp
        src/chapter-3.cpp
        include/chapter-3.h
        src/stack.cpp
        include/stack.h
)
