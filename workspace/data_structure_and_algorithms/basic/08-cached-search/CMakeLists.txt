cmake_minimum_required(VERSION 3.10.2)
project(cached_search)

## Compile as C++11:
SET(CMAKE_BUILD_TYPE "Release")
SET(CMAKE_CXX_FLAGS_RELEASE "$ENV{CXXFLAGS} -O3 -Wall")
add_compile_options(-std=c++11)
add_definitions(-std=c++11)

###########
## Build ##
###########

add_executable(lc_1300_bash_game 
  lc_1300_bash_game.cpp
)

add_executable(lc_0111_climbing_stairs
  lc_0111_climbing_stairs.cpp
)

add_executable(lc_0272_climbing_stairs_ii
  lc_0272_climbing_stairs_ii.cpp
)

add_executable(lc_0683_word_break_iii
  lc_0683_word_break_iii.cpp
)

add_executable(lc_0582_word_break_ii
  lc_0582_word_break_ii.cpp
)

add_executable(lc_0192_wildcard_matching
  lc_0192_wildcard_matching.cpp
)

add_executable(lc_0154_regular_expression_matching
  lc_0154_regular_expression_matching.cpp
)