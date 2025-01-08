add_library(
        navmesh
        point.h point.cpp
        segment.h segment.cpp
        polygon.h polygon.cpp
        path_finder.h path_finder.cpp
        cone_of_vision.h cone_of_vision.cpp
)

target_include_directories(navmesh PUBLIC "${CMAKE_CURRENT_SOURCE_DIR}")
