cmake_minimum_required(VERSION 3.16)
project(Project)

set(CMAKE_CXX_STANDARD 20)

add_executable(Project main.cpp videodata.cpp videodata.h gui.h gui.cpp)