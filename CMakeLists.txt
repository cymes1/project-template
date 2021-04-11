cmake_minimum_required(VERSION 3.11)
set(CMAKE_CXX_STANDARD 20)

project(<<project-name>>)

# set the output directory
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/build/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/build/bin)

# set compilation mode
set(CMAKE_BUILD_TYPE Debug)

# generating compilation database for libclang for YouCompleteMe
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_subdirectory(src)
