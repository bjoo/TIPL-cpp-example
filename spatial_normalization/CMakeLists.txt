add_executable(spatial_normalization spatial_normalization.cpp)
target_link_libraries(spatial_normalization PUBLIC TIPL::tipl)
set_target_properties(spatial_normalization PROPERTIES CXX_STANDARD 14)

file(CREATE_LINK ${CMAKE_SOURCE_DIR}/data ${CMAKE_CURRENT_BINARY_DIR}/data SYMBOLIC)
