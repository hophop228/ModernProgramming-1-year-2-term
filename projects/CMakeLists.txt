cmake_minimum_required(VERSION 3.2...3.27.5)

project(CMake_learn)

enable_testing()
add_subdirectory(lib/googletest)

add_subdirectory(bubble_sort)
add_subdirectory(bubble_sort_mf)
add_subdirectory(refactoring_and_print)
add_subdirectory(base_theory_p1)
add_subdirectory(base_theory_tasks_p1)
add_subdirectory(obuchaika)
#add_subdirectory(unit_test_example)
add_subdirectory(merge_sort)
#add_subdirectory(unit_test_merge_sort)
add_subdirectory(scl_homework)
add_subdirectory(long_number)

set(CMAKE_SUPPRESS_REGENERATION true)
