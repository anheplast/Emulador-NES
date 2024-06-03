cmake_minimum_required(VERSION 3.28)
project(emuladorNES)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(cppCode)

add_executable(emuladorNES
    cppCode/helloWorld.cpp
        Bus.h)
