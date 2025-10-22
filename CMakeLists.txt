cmake_minimum_required(VERSION 3.24)
project(compiler_lab_project_master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.
        C:/msys64/mingw64/include/SDL2)

add_executable(compiler_lab_project_master
        bmp/empty.bmp
        bmp/numbers.bmp
        calculate.c
        main.c
        main.h
        Makefile
        parser.c
        plot.c)
