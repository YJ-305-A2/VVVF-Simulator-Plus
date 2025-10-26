cmake_minimum_required(VERSION 3.31)
project(embedded C ZIG)

set(CMAKE_C_STANDARD 17)
set(ZIG_EXECUTABLE "zig")
add_executable(embedded_target firmware.zig)