cmake_minimum_required(VERSION 3.29)
project(test_git)

set(CMAKE_CXX_STANDARD 14)

add_executable(test_git res/main.cpp
        res/file1.cpp)
