cmake_minimum_required(VERSION 4.2)
project(CXX_List_vs_BST_vs_AVL)

set(CMAKE_CXX_STANDARD 20)

add_executable(CXX_List_vs_BST_vs_AVL main.cpp
        "CPP Files/BST.cpp"
        "Headers/BST.h"
        "CPP Files/AVL.cpp"
        "Headers/AVL.h"
        "CPP Files/DataInsertion.cpp"
        "Headers/DataInsertion.h")
