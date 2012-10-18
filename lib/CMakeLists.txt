
add_library(expatpp SHARED expatpp.cpp)
target_link_libraries(expatpp ${EXPAT_LIBRARIES})
SET_TARGET_PROPERTIES(expatpp PROPERTIES ${EXPATPP_LIBRARY_PROPERTIES})
INSTALL_TARGETS(/${LIB_INSTALL_DIR} expatpp)