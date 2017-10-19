cmake_minimum_required(VERSION 3.6)
project(assignment_1_2)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Room.h Room.cpp Treasure.h Props.h Props.cpp Treasure.cpp FixedObj.h FixedObj.cpp Agent.h Agent.cpp Monster.h Monster.cpp Player.h Player.cpp Object.h Object.cpp)
add_executable(assi2-20150181 ${SOURCE_FILES})