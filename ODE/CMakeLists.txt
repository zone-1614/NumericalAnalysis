aux_source_directory(. ALL_SOURCE)

message("build directory: ${CMAKE_CURRENT_SOURCE_DIR}")

link_eigen("${ALL_SOURCE}")
