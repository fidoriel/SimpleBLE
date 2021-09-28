cmake_minimum_required(VERSION 3.16.0)

project(EXAMPLE_WRITE_HEX)

message("-- [INFO] Building Example")
add_executable(example_write_hex write_hex.cpp)
target_link_libraries(example_write_hex simpleble-static)
