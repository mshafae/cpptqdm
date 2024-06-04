cmake_minimum_required(VERSION 3.10)

project(cpptqdm)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_BUILD_TYPE "Release")

add_executable(${PROJECT_NAME} ${CMAKE_CURRENT_SOURCE_DIR}/test.cpp)

target_include_directories(
        ${PROJECT_NAME} PUBLIC
        ${CMAKE_CURRENT_SOURCE_DIR}
)