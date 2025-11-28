# min version of cmake
cmake_minimum_required(VERSION 3.10)

# name of project
project(BankSystem VERSION 1.0)

file(GLOB SOURCE_FILES "src/*.cpp")

add_executable(BankSystem ${SOURCE_FILES})
target_include_directories(BankSystem PUBLIC include)

