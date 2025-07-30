cmake_minimum_required(VERSION 3.31)
project(Keylogger)

set(CMAKE_CXX_STANDARD 20)

add_executable(Keylogger
        main.cpp
        vkCodes.cpp
        vkcodes.h
)