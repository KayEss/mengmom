cmake_minimum_required(VERSION 3.6)
project(mengmom)

# These contain targets and functions needed elsewhere
add_subdirectory(cord)
add_subdirectory(fost-base)

add_subdirectory(Boost)
add_subdirectory(crypto++)
add_subdirectory(fost-beanbag)
add_subdirectory(fost-internet)
add_subdirectory(fost-postgres)
add_subdirectory(fost-web)
add_subdirectory(fostgres)
add_subdirectory(json-schema)
add_subdirectory(libpqxx)
add_subdirectory(odin)
add_subdirectory(threading)
