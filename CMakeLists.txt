cmake_minimum_required(VERSION 3.6)
project(cbase)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp cbase.h)
add_executable(cbase ${SOURCE_FILES})