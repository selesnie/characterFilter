cmake_minimum_required(VERSION 2.8)

project(characterFilter)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -Wpedantic -Werror -Wno-unused-parameter -std=c++14 -g -fno-strict-aliasing")

add_executable(${PROJECT_NAME} "main.cpp")
