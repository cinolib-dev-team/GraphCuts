cmake_minimum_required(VERSION 3.14)

add_library(graph_cuts
            STATIC
            LinkedBlockList.h
            graph.h
            GCoptimization.h
            energy.h
            block.h
            LinkedBlockList.cpp
            GCoptimization.cpp)

target_include_directories(graph_cuts PRIVATE ${graph_cuts_SOURCE_DIR})
