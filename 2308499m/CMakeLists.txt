cmake_minimum_required(VERSION 3.15)
project(Coursework_code_skeleton)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Coursework_code_skeleton
        driver.c
        driver.h
        firmware.cl
        Makefile
        testbench.c)
