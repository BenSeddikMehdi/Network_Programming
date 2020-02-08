cmake_minimum_required(VERSION 3.15)
project(Network_Programming C)

set(CMAKE_C_STANDARD 99)

add_executable(Network_Programming main.c TCP_Client.c TCP_Client.h)