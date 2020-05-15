cmake_minimum_required(VERSION 3.10)
project(text C CXX)

set(CMAKE_CXX_STANDARD 17)


include_directories(include)
add_executable(main main.cpp)

target_link_libraries(main)