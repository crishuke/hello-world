cmake_minimum_required(VERSION 2.8.5)
project(cmake-helloworld)

file(GLOB_RECURSE CODE
	${CMAKE_CURRENT_SOURCE_DIR}/src/*.cpp
)


add_executable(main ${CMAKE_CURRENT_SOURCE_DIR}/src/main.cpp)
