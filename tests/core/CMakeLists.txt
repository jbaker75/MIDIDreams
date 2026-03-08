add_executable(test_core test_math_utils.c)
target_link_libraries(test_core PRIVATE core)
add_test(NAME CoreTests COMMAND test_core)