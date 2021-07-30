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
