set(CMAKE_TOOLCHAIN_FILE "$ENV{VCPKG_ROOT}/scripts/buildsystems/vcpkg.cmake")

cmake_minimum_required(VERSION 3.20)
project(pipinio)

set(CMAKE_CXX_STANDARD 17)

add_library(${CMAKE_PROJECT_NAME} STATIC src/CPiPinIO.cpp)
