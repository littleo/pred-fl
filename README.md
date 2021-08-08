### PredFL (Learning Augmented Online Facility Location)

This repository contains the source code, datasets and solutions related to a paper submited to NeurIPS 2021. 

1. `dataset` contains the datasets (CoverType, US Census) used to run the experiments for the algorithm presented in the paper. The synthetic dataset was created by randomly sampling 2k points on a grid.
2. `solutions` contains the (optimal) offline linear solutions for each dataset. In order to calculate the optimal solution, we solved the LP-relaxation of facility location using Gurobi version 9, and using deterministic rounding we obtained a 6approximate integer solution.
3. `notebooks` contains three jupyter notebooks corresponding to each dataset. 

If you have any question on the algorithm implemented, please refer to said article.
