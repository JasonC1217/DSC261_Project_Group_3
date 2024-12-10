# Score-based Causal Discovery in Manufacturing Systems

## Overview
This project investigates the application of modern causal discovery methods to manufacturing systems, with the goal of enhancing process understanding and debugging capabilities. We evaluate several state-of-the-art score-based causal discovery algorithms against traditional approaches using the causalAssembly benchmark dataset.

## Key Features
- Implementation and comparison of multiple causal discovery methods:
  - Score-based methods: GES, NOTEARS, DAG-GNN, GOLEM
  - Traditional methods: PC algorithm, LiNGAM
- Evaluation using real manufacturing data with known ground-truth causal relationships
- Comprehensive performance analysis using multiple metrics
- Visualization tools for causal graph interpretation

## Dataset
We use the causalAssembly dataset, which contains:
- Real manufacturing process data
- Known ground-truth causal relationships
- Multiple variables representing different aspects of the manufacturing process

## Methods
Our analysis includes:
1. Score-based methods:
   - GES (Greedy Equivalence Search)
   - NOTEARS
   - DAG-GNN
   - GOLEM

2. Traditional approaches:
   - PC Algorithm (constraint-based)
   - LiNGAM (functional approach)

## Evaluation Metrics
We assess performance using:
- Structural Hamming Distance (SHD)
- F1 Score
- Precision
- Graph visualization comparisons

## Requirements
- Python 3.7+
- pgmpy
- lingam
- networkx
- matplotlib
- scikit-learn
- seaborn
- gcastle

## Usage
The main analysis can be found in `261 final project_code.ipynb`.
To simulate the data, use the notebook `Data_Simulation.ipynb` under the folder "Data" and run all cells.
To run the analysis, use the notebook `261 final project_code.ipynb` and run all cells.

