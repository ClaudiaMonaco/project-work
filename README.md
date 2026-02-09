# Computational Intelligence - Final Project

This repository contains my final project for the Computational Intelligence course.

This project was developed together with Federico Piozzi (s337638). 
All experiments, design choices, and comparisons are documented in the report and in the shared development repository:
https://github.com/federicopiozzi01/Computational_Intelligence_Project


## Repository Structure

- `Problem.py`  
  Defines the problem instance, including graph generation, cost function, and baseline solution.

- `s343397.py`  
  Main entry point of the project.  
  It implements the `solution(p: Problem)` function required for evaluation.

- `src/`  
  Contains auxiliary modules used by the solution, including:
  - cost evaluation functions
  - Genetic Algorithm core components (selection, crossover, mutation, elitism)
  - shortest-path precomputation utilities
  - construction of the final output path in the required format

- `base_requirements.txt`  
  Lists the Python libraries required to run the project.



