cmake_minimum_required(VERSION 2.8.12)
project(calibrate_camera)

find_package(OpenCV 3.0 REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR})
add_executable(calibrate src/calibrate.cpp)
target_link_libraries(calibrate ${OpenCV_LIBS})
