cmake_minimum_required(VERSION 3.0)

project(hello_world
        VERSION 1.0.0
        LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_MACOSX_RPATH 1)

set(HELLO_SOURCES
        hello_world.cpp)

add_executable(hello_world ${HELLO_SOURCES})

