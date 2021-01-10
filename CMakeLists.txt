cmake_minimum_required(VERSION 3.17)
project(cpp_repl_template)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(main src/main.cpp src/main.cpp src/main.h)