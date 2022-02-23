# Introduction

This project is intended to provide a basic implementation of the reduced basis algorithms presented in the paper "A Reduced Basis Method for Fractional Diffusion Operators I" by Tobias Danczul and Joachim Schöberl. The main objective of this paper is the efficient numerical approximation of interpolation norms and fractional differential operators, such as the spectral fractional Laplacian.  

The repository contains two Jupyter Notebook that walk the reader through the code:

- FractionalNorm.ipynb: The file includes
  - a basic implementation of the reduced basis interpolation norm,
  - a numerical example illustrating the performance of the reduced basis interpolation norms on the unit square.  
- FractionalOperator.ipynb: This file contains
  - a basic implementation of the reduced basis operator,
  - numerical examples illustrating the performance of the reduced basis operator
    - on the unit circle,
    - for decreasing mesh-paramerters,
    - on the L-shape domain.

# Technologies

The files are created with:
- NGSolve[^1] v6.2.2105
- Python 2.7.18

[^1]: https://ngsolve.org/ 
 

# References
For more information on model order reduction schemes for fractional diffusion problems, we refer to

- T. Danczul and J. Schöberl. A reduced basis method for fractional diffusion operators II. Journal of Numerical Mathematics, 2021.
- T. Danczul and C. Hofreither. On rational Krylov and reduced basis methods for fractional diffusion. Journal of Numerical Mathematics, 2021.
- T. Danczul, C. Hofreither, and J. Schöberl. A unified rational Krylov method for elliptic and parabolic fractional diffusion problems. arXiv preprint, 2021.
- T. Danczul. Model Order Reduction for Fractional Diffusion Problems, PhD Thesis, 2021
