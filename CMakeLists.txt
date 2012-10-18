
cmake_minimum_required(VERSION 2.6)

project(expatpp)


find_package(EXPAT REQUIRED)

add_subdirectory(lib)
add_subdirectory(test)

SET(CPACK_GENERATOR "RPM")
SET(CPACK_RPM_PACKAGE_SUMMARY "A tiniy object oriented wrapper around expat library")
SET(CPACK_RPM_PACKAGE_NAME "expatpp")
SET(CPACK_RPM_PACKAGE_VERSION 0.6)
SET(CPACK_RPM_PACKAGE_RELEASE 1)
SET(CPACK_RPM_PACKAGE_LICENSE "Mozilla")

INCLUDE(CPack)
