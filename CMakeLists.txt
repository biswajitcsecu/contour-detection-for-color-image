

project(tutorial_contour)

cmake_minimum_required(VERSION 3.9)

find_package(VISP REQUIRED)
include_directories(${VISP_INCLUDE_DIRS})
add_executable(tutorial_contour tutorial_contour.cpp)
target_link_libraries(tutorial_contour ${VISP_LIBRARIES})
