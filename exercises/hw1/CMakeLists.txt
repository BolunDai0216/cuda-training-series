cmake_minimum_required(VERSION 3.18 FATAL_ERROR)
project(hw1 LANGUAGES CXX CUDA)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(hello src/hello_solution.cu)   
# target_include_directories(hello PUBLIC ${CMAKE_CUDA_TOOLKIT_INCLUDE_DIRECTORIES})