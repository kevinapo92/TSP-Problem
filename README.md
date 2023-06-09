# Traveling Salesman Problem (TSP) 

## Introduction
This repository serves as a comprehensive resource for understanding and solving the well-known computational challenge, the Traveling Salesman Problem.
The Traveling Salesman Problem is a classic mathematical problem in computer science and optimization theory. It seeks to find the shortest possible route that a traveling salesman can take to visit a set of cities and return to the starting city, while visiting each city exactly once. This problem has significant real-world applications in areas such as logistics, transportation planning, circuit design, and DNA sequencing.

The TSP is classified as an NP-hard problem, meaning that finding an optimal solution becomes increasingly difficult and time-consuming as the number of cities increases. Due to its combinatorial nature, exhaustive enumeration of all possible routes quickly becomes impractical, necessitating the development of various algorithms and heuristics to tackle this problem efficiently.

This repository aims to provide a comprehensive algorithm for the TSP considering a vertex formulation.

## Formulation
We will code two IP models for one of the most challenging optimization problems in the world: Traveling Salesperson (Salesman) Problem. First, we will use the Dantzig–Fulkerson–Johnson formulation below.

![image](https://github.com/kevinapo92/TSP-Problem/assets/96119396/901235ed-41b2-4c6c-82bd-332391da6d08)

Secondly a reformulated model was proposed considering a edge formulation 

![image](https://github.com/kevinapo92/TSP-Problem/assets/96119396/db031d55-3f09-47d5-a724-fc7a7273c76b)

We have an Excel file that contains a symmetric distance matrix regarding 13 different cities.

## Technologies Used
* Python
* Jupyter Notebook
* Cplex IBM

In this project, I utilized Python as my primary programming language to analyze and manipulate data. Also an CPLEX extension was used to solve the IP problem

## Data Source

[TSP_Data](https://github.com/kevinapo92/TSP-Problem/blob/main/TSP_input.xlsx)

## Analysis and Results

[TSP_Vertex](https://github.com/kevinapo92/TSP-Problem/blob/main/TSP_Vertex.ipynb)
[TSP_Edges](https://github.com/kevinapo92/TSP-Problem/blob/main/TSP_edges.ipynb)


