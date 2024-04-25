# Optimization-Problems
This repo contains different optimization approaches to find the most optimal parameters for the Zener-Hollomon equation.

Steps:
1. Linearize the equation.
2. Minimize the objective function where the objective function is the RMSE between the predicted and the actual values.
3. Include a surrogate function for the Zener-Holloman equation within the objective function to predict the correct coefficients.

