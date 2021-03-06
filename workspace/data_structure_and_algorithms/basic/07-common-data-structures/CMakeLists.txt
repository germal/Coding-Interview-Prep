cmake_minimum_required(VERSION 3.10.2)
project(common_data_structures)

## Compile as C++11:
SET(CMAKE_BUILD_TYPE "Release")
SET(CMAKE_CXX_FLAGS_RELEASE "$ENV{CXXFLAGS} -O3 -Wall")
add_compile_options(-std=c++11)
add_definitions(-std=c++11)

###########
## Build ##
###########

add_executable(lc_0138_subarray_sum 
  lc_0138_subarray_sum.cpp
)

add_executable(lc_0658_first_unique_number_in_data_stream
  lc_0658_first_unique_number_in_data_stream.cpp
)

add_executable(lc_0657_insert_delete_getrandom_amortized_o1
  lc_0657_insert_delete_getrandom_amortized_o1.cpp
)

add_executable(lc_0657_insert_delete_getrandom_exact_o1
  lc_0657_insert_delete_getrandom_exact_o1.cpp
)

add_executable(lc_0134_lru_cache
  lc_0134_lru_cache.cpp
)

add_executable(lc_0004_ugly_number_ii
  lc_0004_ugly_number_ii.cpp
)

add_executable(lc_0954_insert_delete_getrandom_o1_duplicates_allowed
  lc_0954_insert_delete_getrandom_o1_duplicates_allowed.cpp
)

add_executable(lc_0960_first_unique_number_in_data_stream_ii
  lc_0960_first_unique_number_in_data_stream_ii.cpp
)

add_executable(lc_0171_anagram
  lc_0171_anagram.cpp
)

add_executable(lc_0124_longest_consecutive_sequence
  lc_0124_longest_consecutive_sequence.cpp
)

add_executable(lc_0545_top_k_largest_numbers_ii
  lc_0545_top_k_largest_numbers_ii.cpp
)

add_executable(lc_0544_top_k_largest_numbers
  lc_0544_top_k_largest_numbers.cpp
)

add_executable(lc_0486_merge_k_sorted_arrays
  lc_0486_merge_k_sorted_arrays.cpp
)

add_executable(lc_0612_k_closest_points
  lc_0612_k_closest_points.cpp
)