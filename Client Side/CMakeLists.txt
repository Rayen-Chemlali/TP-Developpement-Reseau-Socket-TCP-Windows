cmake_minimum_required(VERSION 3.27)
project(Client_Side C)

set(CMAKE_C_STANDARD 11)

add_executable(Client_Side main.c)

target_link_libraries(Client_Side PRIVATE ws2_32)

