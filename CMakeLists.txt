cmake_minimum_required(VERSION 2.8)
project( Surf)
find_package( OpenCV )
include_directories( ${OpenCV_INCLUDE_DIRS} )
add_executable(Surf surf.cpp )
target_link_libraries( Surf ${OpenCV_LIBS} )