cmake_minimum_required(VERSION 3.13)

project("The Star of Kevin")

if (UNIX AND NOT APPLE)
    set(CMAKE_EXECUTABLE_SUFFIX ".out")
endif()

add_executable("the-star-of-kevin")

add_subdirectory("src")
add_subdirectory("include")