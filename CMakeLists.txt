cmake_minimum_required(VERSION 3.8)
project(cs3358_abm_assignment8)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        dict0.txt
        dict1.txt
        Assign08.cpp
        HashTable.cpp
        HashTable.h)

add_executable(cs3358_abm_assignment8 ${SOURCE_FILES})