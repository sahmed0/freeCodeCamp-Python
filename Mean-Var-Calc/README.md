# Mean-Variance-Standard Deviation Calculator

This project is a solution to the "Mean-Variance-Standard Deviation Calculator" challenge, which is the first project in the **freeCodeCamp Data Analysis with Python** certification.

## Project Description

The goal of this project is to create a function that converts a list of 9 digits into a $3 \times 3$ Numpy array and returns a dictionary containing the mean, variance, standard deviation, max, min, and sum along both axes and for the flattened matrix.

The programme uses the **Numpy** library to perform vectorised calculations for efficiency.

## Features

-   **Input Validation:** Raises a `ValueError` if the input list does not contain exactly 9 elements.
-   **Matrix Conversion:** Reshapes the input list into a $3 \times 3$ matrix.
-   **Statistical Analysis:** Calculates the following for rows (axis 1), columns (axis 0), and the flattened matrix:
    -   Mean
    -   Variance
    -   Standard Deviation
    -   Max
    -   Min
    -   Sum

## Technologies Used

-   **Python 3**
-   **Numpy**

## Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/sahmed0/Mean-Var-Calc.git
    ```
2.  Navigate to the directory:
    ```bash
    cd mean-var-calc
    ```
3.  Install the required dependency:
    ```bash
    pip install numpy
    ```

## Usage

Import the `calculate` function from the script and pass a list of 9 numbers to it.

```python
import mean_var_std

# Example usage
try:
    result = mean_var_std.calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
    print(result)
except ValueError as e:
    print(e)


