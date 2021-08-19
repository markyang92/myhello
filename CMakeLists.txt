cmake_minimum_required(VERSION 3.0.0)

project("recipe_used_cmake")

add_executable(userprog userprog.c)
install(TARGETS userprog DESTINATION bin)


