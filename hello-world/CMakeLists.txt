cmake_minimum_required(VERSION 3.5)
project(hello-world)

set(CMAKE_BUILD_TYPE Debug)
set(CMAKE_CXX_STANDARD 11)

# Top line = one output file (i.e. the compiled program); (multiple) line(s) below = input/source file(s)
add_executable(
        run_program
        main.cpp
)

