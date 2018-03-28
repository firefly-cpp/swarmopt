![particles](https://github.com/SioKCronin/PSO-baselines/blob/master/media/particles.png)

# PSO Baselines

This repo is dedicated to providing high quality implementations of particle swarm optimization algorithms in Python, organized by their application. My hope is that by including a wide variety of algorithms I can help underscore the potential of stochastic process in optimization in general, and perhaps prime the canvas for algorithm innovation.

Particle swarm optimization (PSO) refers to one of several variations of nature-inspired optimization heuristics, originally presented by Eberhart and Kennedy in 1995. In the docs, I have included information on what sets each algorithm apart, and examples of when each might be best applied.  

## Algorithms
### Single Objective 

* Local Best (LBEST_PSO)
* Global Best (GBEST_PSO)
* Unified (UPSO)
* Multispecies ([MSPSO](https://github.com/SioKCronin/swarm-baselines/tree/master/MSPSO))
* Dynamic MultiSpecies ([DMSPSO](https://github.com/SioKCronin/swarm-baselines/tree/master/DMSPSO))
* MultiLayer (MLPSO) 

### Multi Objective

* Dynamic Neighborhood (DNPSO)

### PSO + Q-learning

* Swarm RL (SRL-PSO)
* Q Swarm Optimizer (QSO) 
* Intelligent PSO
* Improved PSO (IPSO)

## Comparison Benchmark Functions

Single objective test functions:
* Sphere Function
* Rosenbrock's Function
* Ackley's Function
* Griewank's Function
* Rastrigin's Function
* Weierstrass Function

Multi objective test functions:
* Lis & Eiben
* Zitzler

PSO + Q-learning:
* CartPole
