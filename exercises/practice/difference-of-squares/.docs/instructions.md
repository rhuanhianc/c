# Difference between the square of the sum and the sum of the squares

In this exercise, you will calculate the difference between the square of the sum and the sum of the squares of the first `N` natural numbers.

## Definitions:

- **Square of the Sum**: The square of the sum of the first `N` natural numbers is calculated by adding all the numbers from 1 to `N`, and then squaring that sum.

  Example for `N = 10`:
  \[
  (1 + 2 + 3 + ... + 10)^2 = 55^2 = 3025
  \]

- **Sum of the Squares**: The sum of the squares of the first `N` natural numbers is calculated by squaring each number and then adding the results together.

  Example for `N = 10`:
  \[
  1^2 + 2^2 + 3^2 + ... + 10^2 = 385
  \]

- **Difference between the square of the sum and the sum of the squares**: The difference is calculated by subtracting the sum of the squares from the square of the sum.

  Example for `N = 10`:
  \[
  3025 - 385 = 2640
  \]

You will be responsible for implementing three functions:

## Tasks:

1. **Implement the function `square_of_sum`**:
   - This function should calculate the square of the sum of the first `N` natural numbers.
   
   Example usage:
   ```c
   square_of_sum(10); // returns 3025
   
2. **Implement the function `sum_of_squares`**:

   - This function should calculate the sum of the squares of the first N natural numbers.
    Example usage:
    ```c
    sum_of_squares(10); // returns 385

2. **Implement the function `difference_of_squares`**:
   - This function should calculate the difference between the square of the sum and the sum of the squares of the first N natural numbers.
    Example usage
   ```c
    difference_of_squares(10); // returns 2640

## Additional Information:
 - Input: The value of N will be a positive integer.
 - Output: Each function should return an integer corresponding to the result of its operations.
