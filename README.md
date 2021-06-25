# Marginal Posterior Sampling for Slate Bandits
Code implementing algorithms and reproducing results for the paper [Marginal Posterior Sampling for Slate Bandits](https://www.ijcai.org/proceedings/2019/0308.pdf).
Coded by: Maria Dimakopoulou
 
## Overview

 The repository contains three Jupyter Notebook files:
 - `algorithms.ipynb`: implements the following slate bandit algorithms (Section 4 of the paper):
     1. K-armed Bernoulli bandit
     2. generalized linear model bandit
     3. marginal posterior sampling bandit
 - `simulate.ipynb`: runs the algorithms for environments with various number of slots, various actions per slot and additive or non-additive slate link functions (Section 5 of the paper).
 - `visualize.ipynb`: produces the figures and table data of Section 5 of the paper from the results of the simulations.
 
 ## Citing
If you use implementations of this repository in your work, please cite the paper with the following: 
```
@inproceedings{dimakopoulou2019marginal,
  title={Marginal Posterior Sampling for Slate Bandits.},
  author={Dimakopoulou, Maria and Vlassis, Nikos and Jebara, Tony},
  booktitle={IJCAI},
  pages={2223--2229},
  year={2019}
}
```
