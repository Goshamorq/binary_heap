cmake_minimum_required(VERSION 3.19)
project(binary_heap)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_FLAGS_RELEASE "-O3")
add_executable(binary_heap main.cpp Heap_Array.hpp Set_Array.hpp Set_Vector.hpp Heap_Node.hpp tests.hpp Set_Node.hpp functions.hpp)