cmake_minimum_required(VERSION 3.26)
project(OpenCV_demo)

set(CMAKE_CXX_STANDARD 17)

find_package(OpenCV CONFIG REQUIRED)

add_executable(OpenCV_demo main.cpp)
target_link_libraries(OpenCV_demo PRIVATE ${OpenCV_LIBRARIES})
