cmake_minimum_required(VERSION 3.24)
project(redis_client)

set(CMAKE_CXX_STANDARD 17)

add_executable(redis_client main.cpp common.h)
