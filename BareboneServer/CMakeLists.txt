cmake_minimum_required(VERSION 3.27)
project(BareboneServer)

set(CMAKE_CXX_STANDARD 17)

add_executable(BareboneServer main.cpp)

target_link_libraries(BareboneServer ws2_32)