cmake_minimum_required(VERSION 3.5.0)
project(3.7 VERSION 0.1.0 LANGUAGES C CXX)

add_executable(3.7 src/main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
