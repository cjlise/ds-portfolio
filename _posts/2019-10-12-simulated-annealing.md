---
title: "Metaheuristics Project: Simulated Annealing"
date: 2019-10-12
tags: [metaheuristics, optimization, data science]
header: 
   image: "/images/annealing/annealing.png"
excerpt: "metaheuristics, optimization, data science"
---

# Simulated Annealing Lab Report
The goal of this lab is to find the global minimum of a function that has several loacal minima. 

## Function definition
```python
def fitnessFunc(x):
    m = 1 + math.cos(0.04 * x)**2
    n = math.exp(-x**2/20000.0)
    return m * n 
```

## Wave fitness plot
<img src="https://github.com/cjlise/DSTI-projects/blob/master/python_WaveFitness.png" alt="">


	