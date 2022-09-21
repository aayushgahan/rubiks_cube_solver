cmake_minimum_required(VERSION 3.23)
project(rubiks_cube_solver)

set(CMAKE_CXX_STANDARD 14)

add_executable(rubiks_cube_solver main.cpp Model/RubiksCube.cpp Model/RubiksCube.h)
