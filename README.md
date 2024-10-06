# [MOOC Mathematical Optimization for Engineers](https://www.edx.org/learn/math/rwth-aachen-university-mathematical-optimization-for-engineers)

Lab files for the MOOC "Mathematical Optimization for Engineers"

You can download the files and run the code on your local machine and save your progress.

## Setup

```bash
conda env create -f environment.yml
conda activate mooc-mathematical-optimization-for-engineers
```

## Syllabus

Week 1: Introduction and math review

- Mathematical definitions of objective function, degrees of freedom, constraints and optimal solution with real-world examples
- Review of some mathematical basics needed to take us through the course

Week 2: Unconstrained optimization

- Basics of iterative descent: step direction and step length
- Common algorithms like steepest descent, Newton’s method and its variants and trust-region methods.

Week 3: Linear optimization

- KKT conditions of optimality for constrained problems
- Simplex method
- Interior point methods

Week 4: Nonlinear optimization

- Penalty, log-barrier and SQP methods

Mixed-integer optimization

- Branch and bound method for mixed-integer linear problems

Week 5: Global optimization

- Branch and bound method for nonlinear non-convex problems
- Constructing relaxations
- Different formulations and their numerical performance
- Stochastic methods, genetic algorithm and derivative free methods

Week 6: Dynamic optimization

- Full discretization, single-shooting and multi-shooting methods
- Nonlinear model predictive control

Week 7: Machine learning for optimization

- Mechanistic, data-driven and hybrid modelling
- Basics of training machine learning models
- Optimization with machine learning embedded

Week 8: Optimization under uncertainty

- Parametric optimization
- Two stage stochastic problems
- Robust optimization via semi-infinite problems
