cmake_minimum_required(VERSION 3.17)
project(tinyTcpScanner C)

set(CMAKE_C_STANDARD 11)

set(CMAKE_C_FLAGS -lpthread)

add_executable(tinyTcpScanner main.c)