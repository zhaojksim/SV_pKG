# SV_pKG
![Language](https://img.shields.io/badge/language-JupyterNotebook-brightgreen)
![License](https://img.shields.io/badge/license-Apache2.0-yellow)
## Overview
SV_pKG is a computational framework for the Shapley value (SV) based sensitivity analysis on policy-augmented knowledge graphical (pKG) hybrid model in the context of biomanufacturing. It aims to quantify the impact various input variables in bioprocess on the output of interest. Currently, it includes three illustrative Jupyter files:
## Performance comparison 
   The source code of 4 kinds of permutation sampling methods and performance comparison based on the linear Gaussian pKG model:
   - Box-Muller Transformation
   - Spherical Coordinate Transformation
   - TFWW Transfermation
   - TFWW Transfermation + Variance Reduction Techniques
## SV nonlinear
   The source code of simulation-based SV analysis on the nonlinear pKG model, including 2 types of input variables:
   - Random inputs
   - Policy parameters
## SV linear
   The source code of SV analysis on the linear Gaussian pKG model, including:
   - SV calculation for random inputs with analytical formula
   - SV estimation for policy parameters with reusing calculation

