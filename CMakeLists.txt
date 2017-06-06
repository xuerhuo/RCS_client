cmake_minimum_required(VERSION 3.7)
project(RCS_client)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES Rcs_client.cpp RCS_client.h)
add_executable(RCS_client ${SOURCE_FILES})