cmake_minimum_required(VERSION 3.20)
project(miniCompiler LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(MiniCompiler
        src/main.cpp
)

target_include_directories(MiniCompiler PRIVATE
        ${CMAKE_SOURCE_DIR}/src
)
