cmake_minimum_required(VERSION 2.8.7)
project(BinarySearchTree)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES examples/main.cpp include/BinarySearchTree.h source/BinarySearchTree.cpp)
add_executable(BinarySearchTree ${SOURCE_FILES})

install (DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/include  DESTINATION include)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include/)

