cmake_minimum_required(VERSION 3.18 FATAL_ERROR)
project(hw1 LANGUAGES CXX CUDA)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(hello src/hello_solution.cu)
add_executable(vector_add src/vector_add_solution.cu)
add_executable(matrix_mul src/matrix_mul_solution.cu)