cmake_minimum_required(VERSION 3.0.0)
project(flutter_application_select_major VERSION 0.1.0)

include(CTest)
enable_testing()

add_library(flutter_application_select_major flutter_application_select_major.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
