
add_library(expatpp SHARED expatpp.cpp)
target_link_libraries(expatpp ${EXPAT_LIBRARIES})
INSTALL_TARGETS(/lib expatpp)