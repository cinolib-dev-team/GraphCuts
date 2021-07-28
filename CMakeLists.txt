cmake_minimum_required(VERSION 3.14)

add_library(graph_cuts
    LinkedBlockList.h
    graph.h
    GCoptimization.h
    energy.h
    block.h
    maxflow.cpp
    LinkedBlockList.cpp
    graph.cpp
    GCoptimization.cpp)
