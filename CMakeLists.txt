cmake_minimum_required(VERSION 3.27)
project(TcpCppServer)

set(CMAKE_CXX_STANDARD 17)

add_executable(TcpCppServer main.cpp)
target_link_libraries(TcpCppServer ws2_32)

