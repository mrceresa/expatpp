project(expatpp)

find_package(EXPAT required)

add_library(expatpp SHARED expatpp.cpp)
target_link_libraries(expatpp ${EXPAT_LIBRARIES})