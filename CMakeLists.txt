cmake_minimum_required (VERSION 3.8)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project ("Wrapper")

add_executable (Wrapper "Main.cpp" "Wrapper.h" "Engine.h" "Subject.h")