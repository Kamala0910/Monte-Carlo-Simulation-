# Monte-Carlo-Simulation
Monte Carlo Simulation for Estimating π

# Overview
This project implements a Monte Carlo Simulation to estimate the value of π by randomly generating points within a unit square and determining how many fall inside the unit circle. This method illustrates the power of statistical sampling and probability in estimating mathematical constants.

# Introduction to Monte Carlo Simulation
A Monte Carlo Simulation is a mathematical technique used to estimate the possible outcomes of uncertain events. The method was invented by John von Neumann and Stanislaw Ulam during World War II to improve decision-making under uncertain conditions. It was named after the well-known casino town of Monaco, as the element of chance is core to the modeling approach, similar to a game of roulette. Monte Carlo simulations are also utilized for long-term predictions due to their accuracy.

# Simulation Activity: Estimation of π
Experiment Description
The experiment involves randomly generating points within a unit square (with sides of length 1) and determining whether each of these points falls inside the unit circle.

Event: Check if the randomly generated point falls inside the unit circle or not.
Conditions:
if x^2+y^2≤1: The point lies inside the circle.
else: The point lies outside the circle.

# Estimation Method
The value of π is estimated based on the ratio of points that fall inside the circle to the total points generated. This ratio approximates π/4, and multiplying by 4 gives the estimated value of π.

| Sample Points (n) | Estimated Value of π (p) |
|-------------------|--------------------------|
| 10                | 2.8                      |
| 100               | 3.4                      |
| 1,000             | 3.176                    |
| 100,000           | 3.143                    |
| 10,000,000        | 3.141                    |


# Inference
- As the number of sample points (n) increases, the estimated value of π converges toward the actual value of π (approximately 3.14159).
- The initial estimates show significant variation with fewer sample points, indicating a higher level of uncertainty.
- With just 10 points, the estimate of π is 2.8, which is far from the actual value.
- Increasing the sample size to 100 points improves the estimate to 3.4, showing that more data leads to better accuracy.
- At 1,000 points, the estimate becomes 3.176, which is much closer to the actual value.
- With 100,000 points, the estimate of π is 3.143, demonstrating a further reduction in estimation error.
- Finally, using 10,000,000 points yields an estimate of 3.141, which is remarkably close to the actual value of π.

This experiment highlights the effectiveness of the Monte Carlo method in approximating values through probabilistic sampling.

# Technologies Used
Python
NumPy
Matplotlib

# Conclusion
This project showcases the effectiveness of the Monte Carlo method in estimating mathematical constants through simulation. It provides insights into how statistical sampling can be applied to solve real-world problems.


