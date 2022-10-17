cmake_minimum_required(VERSION 3.23)
project(boom)

set(CMAKE_CXX_STANDARD 14)

add_executable(boom main.cpp http_server.cpp http_server.h)
