cmake_minimum_required(VERSION 3.27)
project(Server_Side C)

set(CMAKE_C_STANDARD 11)

add_executable(Server_Side main.c)
target_link_libraries(Server_Side PRIVATE ws2_32)
