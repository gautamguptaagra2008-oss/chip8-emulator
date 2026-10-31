cmake_minimum_required(VERSION 3.20)
project(chip8 CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(chip8 src/main.cpp)

if(MSVC)
    target_compile_options(chip8 PRIVATE /W4)
else()
    target_compile_options(chip8 PRIVATE -Wall -Wextra)
endif()
