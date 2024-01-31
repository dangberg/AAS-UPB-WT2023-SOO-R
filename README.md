# Automated Algorithm Selection on Continuous Black-Box Problems

## Introduction

This project attempts to reproduce the procedure and results achieved by [Kerschke et al.](https://doi.org/10.1162/evco_a_00236) and [Prager et al.](https://link.springer.com/chapter/10.1007/978-3-031-14714-2_1).
In addition, the feature normalization presented in [Prager & Trautmann](https://link.springer.com/chapter/10.1007/978-3-031-30229-9_27) is taken into account.

## Quickstart

1. Install required packages (all listed in the first notebook cell)
2. Inside a section execute the cells in order (the sections itself are independent of each other)
   - In model training, the cells for training the models can also be executed independently of each other
3. Sections *Feature calculation* and *relERT conversion* can be skipped to train the models as all features and relERT are already precomputed
4. The results for the different models are also already available, so it is also possible to visualize only the results using the last section
