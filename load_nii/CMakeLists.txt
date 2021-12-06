add_executable(load_nii load_nii.cpp)
target_link_libraries(load_nii PUBLIC TIPL::tipl)
set_target_properties(load_nii PROPERTIES CXX_STANDARD 14)

file(CREATE_LINK ${CMAKE_SOURCE_DIR}/data ${CMAKE_CURRENT_BINARY_DIR}/data SYMBOLIC)
