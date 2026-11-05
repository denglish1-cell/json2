add_library(libjson Boolean.cpp Boolean.hpp Data.hpp Null.cpp Null.hpp Number.cpp Number.hpp String.cpp String.hpp json.hpp)
target_include_directories(libjson INTERFACE "${CMAKE_CURRENT_SOURCE_DIR}")