cmake_minimum_required(VERSION 3.22)
project(mkinitfs LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)

FILE(GLOB_RECURSE SRC ./src/*.cpp ./src/*.hpp)

add_executable(mkinitfs ${SRC})
