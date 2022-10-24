cmake_minimum_required(VERSION 2.6.0)

include_directories(include)

file(GLOB_RECURSE SOURCES )

add_executable(myprogram main.c)