This repository contains the code and data used for the optimization of animal component-free media for CHO-K1 cell cultures using Dynamic Flux Balance Analysis (dFBA).
The optimization framework combines a genome-scale metabolic model of CHO-K1 cells with linear programming to identify medium formulations that minimize cost while maintaining target growth performance and satisfying metabolic, uptake, and toxicity constraints.

**Title:** Media Design for CHO-K1 Batch Cultures: Integrating Dynamic Flux Balance Analysis with Experimental Validation

**Authors:** Bárbara Ariane Pérez Fernández, Lisandra Calzadilla, Roberto Mulet.

**Requirements**
The code was developed in Julia.
Required packages include:
JuMP
GLPK
DataFrames
CSV
Statistics
Random
