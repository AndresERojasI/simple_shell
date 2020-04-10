cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(SimpleShell VERSION 1.0.0)

file(MAKE_DIRECTORY output)
set(HEADERS headers/holberton.h)
add_executable(hsh 0_main.c)