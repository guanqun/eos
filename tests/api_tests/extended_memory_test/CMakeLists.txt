file(GLOB SOURCE_FILES "*.cpp")
add_wast_target(extended_memory_test "${SOURCE_FILES}" "${CMAKE_SOURCE_DIR}/contracts" ${CMAKE_CURRENT_BINARY_DIR})
