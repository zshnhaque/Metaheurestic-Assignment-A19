
# Shifted Greiwank Problem
##This is implemented using 'pygmo' package.

One can install pygmo on cmd, anaconda or google colab using - 

pip install pygmo

## Class Shifted Greiwank creates F5 problem and it takes Dimension (D) as arguement, D = 50 or 500

## To find best solution for a problem.
1. Create problem object using problem class
2. Continuous Optimization algorithm functions are initialised along with their parameters.
3. Call calc_fitness() function which takes problem object from step 2, algorithm object from step 2 and population size.
4. Evaluate the result from step 4.
