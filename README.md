# Implementation-of-Metropolis-and-Wolff-algorithm-on-Ising-model-in-python

## Introduction

This project explores the Metropolis algorithm and its implementation on 2D Ising
model in great detail. Monte Carlo methods are discussed to understand the similarities of
interactions in the computer model of spins and the systems in real life.
The goal of this project is to explore the scope of the Metropolis algorithm in un-
derstanding various aspects of phase transitions. Also, the limitations and drawbacks of the
Metropolis algorithm near the critical region are discussed. Working of Wolff algorithm to
overcome such issues is also discussed in the project.
Simulation of finite size scaling is implemented to obtain the critical exponents.

## Monte Carlo simulation
The Monte Carlo simulation has been used to calculate the partition function of the Ising
model. It simulates the random thermal fluctuations of the system from state to state. For
calculating the microscopic properties we take the expectation value as a time average over
all the states system go through while simulation. In a complete Monte Carlo calculation, we
create a model on our computer and make it pass through a variety of steps in such a way that
the probability of finding that system in that particular state at that time t is equal to that 
system would have in a real life.

## The Metropolis Algorithm
Metropolis algorithm is the most preliminary algorithm of the Monte Carlo methods.
Here the ideas of the metropolis algorithm are discussed with the help of the Ising model. Ising
model is a simple model of up and down spins on a finite lattice.

## Optimization of the python code
The entire coding is done in Python because it is very intuitive and easy to understand lan-
guage. But, python is slower than C because it is an interpreted language. That increases the
number of actual CPU instructions required to perform the task. The Python code is optimized
using Numba. Numba translates Python functions to optimized machine code at runtime us-
ing the industry-standard LLVM compiler library.

## Outline of the project

*   Define all componets of Ising model
*   Define Metropolis Algorithm
    *   lattice visualization
    *   Quick simulation of metropolis algorithm on 5x5 lattice to ensure everything is working fine, before implementing on 100x100 lattice.
*   Implementation on 100x100 lattice
    *   Equilibration
    *   Measurements
    *   Correlation time
    *   Calculation of thermodynamic quantities
    *   Calculation of errors
*   Collecting measurements for different lattice sizes
    * L=50
    * L=64
    * L=100
    * L=120
*   Finite size scaling 
    * critical exponents
    * errors on critical exponents

*   Tackling the problem of critical slow down with Wolff's Algorithm
    * L = 50
    * L = 64

## Suggestions/Queries
Email me at saurabh.annadate9@gmail.com
