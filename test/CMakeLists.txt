
include_directories (${expatpp_SOURCE_DIR}/lib)
link_directories (${expatpp_BINARY_DIR}/lib ${EXPAT_INCLUDE_DIR})

add_executable (testexpatpp1 testexpatpp.cpp)

target_link_libraries (testexpatpp1 expatpp) 