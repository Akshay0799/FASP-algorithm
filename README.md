# FASP-algorithm
Source code for the Inderscience paper titled "Favourable subpopulation migration strategy for Travelling salesman problem" 

## Abstract
Most of the existing migration strategies are complex in nature that results in high computation time. Since the introduction of parallel genetic algorithms, they are known for obtaining better optimal solutions at the cost of more computation. Migration has played a significant role in maintaining genetic diversity of the population.  This paper aims to propose a new migration strategy that improves the performance of the parallel genetic algorithm and assess its behaviour under various Travelling Salesman Problem datasets. The algorithm is based on an island model approach where one subpopulation is nurtured by the other subpopulations by taking turns during the migration process to progressively reach the optimal solution. In turn, the nurtured subpopulation provides a feedback loop to the subpopulation with poor fitness value based on certain criterias to be met. An extensive study was conducted to understand the optimal parameters values in which the proposed algorithm works best.

## Proposed Algorithm
![image](https://user-images.githubusercontent.com/30732059/118697989-889d9580-b82d-11eb-95d6-6e1a57c41d63.png)



## Comparison of FASP performance in various datasets

**The result is represented as the percentage improvement between the initial
distance and final distance in the following graphs for 2 different cases respectively**


### Percentage Improvement by varying the number of Generations


<img src="https://user-images.githubusercontent.com/30732059/118699807-99e7a180-b82f-11eb-87a7-bcb7cc1a6e8b.png" width="800">

### Percentage Improvement by varying the Migration Interval


<img src="https://user-images.githubusercontent.com/30732059/118699628-5e4cd780-b82f-11eb-8d02-bbeebc61b539.png" width="800">


#### _For a detailed analysis, refer our paper : https://dx.doi.org/10.1504/ijbidm.2022.10035424_
The base code for the Genetic algorithm was implemented from [here](https://towardsdatascience.com/evolution-of-a-salesman-a-complete-genetic-algorithm-tutorial-for-python-6fe5d2b3ca35)
