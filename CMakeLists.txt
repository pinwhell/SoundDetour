cmake_minimum_required(VERSION 3.15)

project(SoundDetour)

add_compile_options(/MT$<$<CONFIG:Debug>:d>)

add_subdirectory(vendor)
add_subdirectory(src)
add_subdirectory(tests)