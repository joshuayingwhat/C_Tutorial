cmake_minimum_required(VERSION 3.20)
project(C_Tutorial C)

set(CMAKE_C_STANDARD 99)

add_executable(C_Tutorial main.c integer_types.c integer_types.h float_point.h float_point.c variable.h variable.c)
