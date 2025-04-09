# Mean-Variance-Standard Deviation Calculator

This is the boilerplate for the Mean-Variance-Standard Deviation Calculator project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/mean-variance-standard-deviation-calculator

## 🧠 About the Project

The goal is to create a Python function that:
- Takes a list of 9 numbers as input
- Converts it into a 3x3 NumPy matrix
- Calculates the following statistics:
  - Mean
  - Variance
  - Standard deviation
  - Max
  - Min
  - Sum

Each of the above is calculated across:
- Axis 0 (columns)
- Axis 1 (rows)
- Flattened matrix

If the input list has fewer than 9 numbers, the function raises a `ValueError`.