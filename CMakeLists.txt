cmake_minimum_required(VERSION 3.10)

project(ConsoleTerminalOperatingSystem)

set(CMAKE_C_STANDARD 11)

add_executable(ctos
    src/main.c
    src/libc/stdio2.h
    src/header.h
    src/minio.h
)