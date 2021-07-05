cmake_minimum_required(VERSION 3.10)


set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++2a ") # -fcoroutines -fconcepts-diagnostics-depth=2 -march=native -msse4.1 -msse3 -msse2 -mpopcnt -mbmi2 -mbmi
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

include_directories(include)
add_executable(out src/main.cpp)
