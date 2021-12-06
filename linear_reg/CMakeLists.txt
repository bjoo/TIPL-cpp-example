add_executable(linear_reg linear_reg.cpp)
target_link_libraries(linear_reg PUBLIC TIPL::tipl)
set_target_properties(linear_reg PROPERTIES CXX_STANDARD 14)

file(CREATE_LINK ${CMAKE_SOURCE_DIR}/data ${CMAKE_CURRENT_BINARY_DIR}/data SYMBOLIC)
