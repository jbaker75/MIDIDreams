cmake_minimum_required(VERSION 3.16)
project(MIDIDreams VERSION 0.1 ENABLED_LANGUAGES C CXX)

set(CMAKE_C_STANDARD 11)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

find_package(Qt6 REQUIRED COMPONENTS Widgets Test)
qt_standard_project_setup()

add_subdirectory(src/core)
add_subdirectory(src/ui)
add_subdirectory(widgets)
add_subdirectory(tests)