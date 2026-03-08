add_library(core STATIC 
    math_utils.c
)
target_include_directories(core PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})