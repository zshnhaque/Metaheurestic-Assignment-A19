# Discrete Optimization - Travelling Salesman Problem

This is implemented using 'jmetalpy' package.

## JMetalPy installation
One can install jmetalpy on cmd, anaconda or google colab using - 

pip install jmetalpy

## Downloading TSP files

!curl http://www.math.uwaterloo.ca/tsp/world/dj38.tsp -o dj38.tsp

!curl http://www.math.uwaterloo.ca/tsp/world/qa194.tsp -o qa194.tsp

## Creating Travelling Salesman Problem class (for Symmetric TSP)

Here, .tsp file is read .
<br/>Distance Matrix is computed which is fed to GA Function.

## Solving TSP problem using Genetic Algorithm

Call the function 'calc_tsp_ga' which takes arguments -
1. File location for .tsp file
2. Population Size
3. Offspring Population Size
4. maximum number of evaluations
