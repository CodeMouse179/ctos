cmake_minimum_required(VERSION 3.26)

set(CMAKE_C_STANDARD 11)

set(CMAKE_CXX_STANDARD 11)

project(ConsoleTerminalOperatingSystem)

add_executable(ctos
    src/main.c
    src/libc/stdio2.h
    src/header.h
    src/minio.h
)