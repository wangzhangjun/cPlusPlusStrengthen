cmake_minimum_required(VERSION 3.14)
project(c___stl)

set(CMAKE_CXX_STANDARD 14)

add_executable(c___stl main.cpp string.cpp test_Vector.cpp deque.cpp stack.cpp queue.cpp list.cpp priority_queue.cpp set.cpp multiset.cpp map.cpp multimap.cpp)