configure_file(${CMAKE_CURRENT_SOURCE_DIR}/include/BookshopConfig.h.in ${CMAKE_CURRENT_SOURCE_DIR}/include/BookshopConfig.h)

include_directories(include)

add_subdirectory(src)
