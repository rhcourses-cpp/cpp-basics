cmake_minimum_required(VERSION 3.28)
project(cpp_basics)

set(CMAKE_CXX_STANDARD 20)

add_executable(cpp_basics main.cpp)

cmake_path(SET GITIGNORE_FILE NORMALIZE "${CMAKE_BINARY_DIR}/.gitignore")
file(WRITE ${GITIGNORE_FILE} "*")
