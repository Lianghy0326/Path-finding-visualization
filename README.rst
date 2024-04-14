=============================
Path Finding Using Algorithms
=============================

Basic Information
=================

Github Repository: https://github.com/Lianghy0326/Path-finding-visualization
This program is designed to efficiently solve differential equations, 
focusing on equations with constant coefficients, Legendre, and Cauchy-Euler forms.

Problem to Solve
=================

The primary goal of this project is to implement various pathfinding algorithms, including A*, DFS, etc., and visualize the paths they generate.

Prospective Users
=================

The prospective users of this project are researchers and developers who have requirements for pathfinding in large-scale environments.

System Architecture
===================

This library will be developed in ``C++`` .
``Python`` library will be used if nessesary.
* ``C++``: Used to implement the algorithm .


API Description
===============

The ``C++`` API::

    // Find a path using A* algorithm
    Path find_path_a_star(const Grid& grid, const Point& start, const Point& goal);

    // Find a path using Depth-First Search algorithm
    Path find_path_dfs(const Grid& grid, const Point& start, const Point& goal);


The ``Python`` API::

    # Find a path using A* algorithm
    path_a_star = find_path_a_star(grid, start, goal)

    # Find a path using Depth-First Search algorithm
    path_dfs = find_path_dfs(grid, start, goal)


Engineering Infrastructure
==========================

* ``make``: Used to build the software system.
* ``git``: Used for version control.
* ``pytest``: Used for unit testing.

Schedule
========

* Week 1 (04/08): Research on A* algorithm and DFS.
* Week 2 (04/15): Implement basic data structures and design input data for testing.
* Week 3 (04/22): Implement A* algorithm.
* Week 4 (04/29): Implement DFS algorithm.
* Week 5 (05/06): Visualizing and debugging for both algorithms.
* Week 6 (05/13): Implement additional pathfinding algorithms.
* Week 7 (05/20): Testing and debugging for all implemented algorithms.
* Week 8 (05/27): Prepare the presentation.

References
==========
