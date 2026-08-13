Where's Waldo Path Optimization

A computational project that uses a Genetic Algorithm (GA) to determine an efficient search path for finding Waldo across the known Waldo locations from the first seven Where's Waldo? books.

The project is based on the methodology presented in Randal S. Olson's work, "Here's Waldo: Computing the optimal search strategy for finding Waldo." The provided notebook contains the data analysis, visualization, genetic algorithm implementation, and optimization process.

Project Overview

Finding Waldo efficiently can be formulated as a path-optimization problem:

Given a set of known Waldo locations, what ordering of those locations produces the shortest overall search path?

The project contains 68 known Waldo locations distributed across 7 books and 12 pages. Each location is represented by its book, page, and normalized (X, Y) coordinates.

The optimization objective is to find an ordering of all 68 locations that minimizes the total Euclidean distance traveled between consecutive locations.
