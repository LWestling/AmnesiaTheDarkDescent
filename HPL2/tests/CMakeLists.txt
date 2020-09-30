cmake_minimum_required (VERSION 2.8.11)
project(HPL2_TESTS)

set(HPL2_TESTS_VERSION_MAJOR 2)
set(HPL2_TESTS_VERSION_MINOR 0)

file(GLOB all_sources RELATIVE ${CMAKE_CURRENT_SOURCE_DIR}
        src/Common/*.cpp
        src/Common/*.h
        )