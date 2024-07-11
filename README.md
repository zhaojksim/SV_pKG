# SV_pKG
## Overview
SV_pKG is a computational framework for the Shapley value (SV) based sensitivity analysis on policy-augmented knowledge graphical (pKG) hybrid model in the context of biomanufacturing. It aims to quantify the impact various input variables in bioprocess on the output of interest. Currently, it includes following module:
1. pKG modeling
2. Permutation sampling
   - TFWW transformation
   - Randomized quasi-Monte Carlo and antithetic sampling
3. SV estimation
   - Nonlinear pKG model
   - Linear Gaussian pKG model
4. Experiment data for fed-batch fermentation of Yarrowia lipolytica
