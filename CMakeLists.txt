cmake_minimum_required(VERSION 3.13)
project(sample_project)

set(CMAKE_CXX_STANDARD 98)

add_executable(sample_project main.cpp rsdl.cpp rsdl.hpp Circle.cpp Circle.h Game.cpp Game.h)