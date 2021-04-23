cmake_minimum_required(VERSION 3.10)

project(cmake_test_00)

set(SOURCE_FILES hellofunc.c hellomake.c hellomake.h)

add_executable(hellomake ${SOURCE_FILES})


