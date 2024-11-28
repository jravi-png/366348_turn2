project(ui)

set(SOURCE_FILES ui.cpp ui.h)
add_library(ui ${SOURCE_FILES})

target_include_directories(ui PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
target_link_libraries(ui core)