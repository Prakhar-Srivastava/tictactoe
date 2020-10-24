cmake_minimum_required(VERSION 3.12)
project(tictactoe)

set(CMAKE_CXX_STANDARD 14)

include_directories(lib)

add_executable(tictactoe
		lib/components.hpp
		tests/test.cpp
		)
