cmake_minimum_required(VERSION 3.29)
project(Genetic_Algorithm)

set(CMAKE_CXX_STANDARD 20)

add_executable(Genetic_Algorithm main.cpp
        GeneticAlgorithm/GeneticAlgorithm.cpp
        Chromosome/Chromosome.cpp
        Utilities/StaticData.cpp)
