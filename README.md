# DAA-lab
# Practical 1: Sorting Algorithms
This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search
This practical implements the Linear Search algorithm with interactive user input. It demonstrates:

Implementation of linear search that returns the index of the target (or -1 if not found).
Measurement of execution time using time.perf_counter().
Time complexity analysis (Best, Average, Worst cases).
Usage:

Interactive: run the script and follow prompts to provide the list and target value.
Demo: run the script with a demo flag (if provided in the script).
linear search
binary search
# Practical 3: Max-Heap and Min-Heap Sort
Aim

To implement Min-Heap and Max-Heap Sort in Python.

Description Min-Heap Sort: Sorts elements in ascending order. Max-Heap Sort: Sorts elements in descending order. Execution time is measured using time.perf_counter(). Time Complexity Best Case: O(n log n) Average Case: O(n log n) Worst Case: O(n log n) Conclusion

Min-Heap and Max-Heap Sort were successfully implemented to sort elements in ascending and descending order respectively.

# Practical-4:Factorial of ieterative and recursive function
In this practical, we learned how to find the factorial of a number using two different methods: iterative and recursive. In the iterative method, we use a loop to multiply the numbers from 1 to the given number. In the recursive method, the function calls itself with a smaller value until it reaches the base condition. Both methods give the same factorial result, but they work in different ways.

CONCLUSION:

From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem. CONCLUSION:

From this practical, we understood the difference between iterative and recursive approaches for solving a problem. Both methods are useful for calculating factorials, and this practical helped us understand how loops and recursion can be used to solve the same problem.

# practical-5: Knapsack Problem
This project is a Python program that solves the 0/1 Knapsack Problem using Dynamic Programming. The program takes the number of items, their weights, values, and the maximum capacity of the knapsack as input. It then finds the maximum value that can be carried without exceeding the given capacity. The program also displays the selected items and the execution time. This project is simple and useful for understanding the basic concept of Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named knapsack.py and run it using the command python knapsack.py in the terminal.

Example

For 4 items with weights 2, 3, 4, 5 and values 3, 4, 5, 6, with a knapsack capacity of 5, the maximum value is 7 and items 1 and 2 are selected.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the 0/1 Knapsack Problem. It helps in finding the best combination of items while keeping the total weight within the given capacity. The project is simple and helpful for learning Python and Dynamic Programming.

# PRACTICAL-6 MATRIX CHAIN MULTIPLICATION
Matrix Chain Multiplication is a Dynamic Programming problem that finds the most efficient way to multiply a sequence of matrices.

The main objective is to determine the optimal order of matrix multiplication that minimizes the total number of scalar multiplications. The order of the matrices remains unchanged; only the placement of parentheses is optimized.

This project implements the Matrix Chain Multiplication algorithm using Python and Dynamic Programming.

# PRACTICAL 7:Coin Change Problem Using Dynamic Programming
This project provides a Python solution to the Coin Change Problem using Dynamic Programming. The program determines the minimum number of coins required to make a given target amount from a set of available coin denominations.

The algorithm builds a dynamic programming table to store the minimum coins needed for every amount from 0 to the target value. By reusing previously computed results, it efficiently finds the optimal solution and avoids redundant calculations.

If the target amount can be formed, the program returns the minimum number of coins required. Otherwise, it returns -1 to indicate that no valid combination exists.

Features Efficient Dynamic Programming approach Finds the minimum number of coins required Handles impossible cases by returning -1 Simple and easy-to-understand Python implementation Complexity Time Complexity: O(n × amount) Space Complexity: O(amount) This project is useful for learning Dynamic Programming concepts, practicing algorithm design, and preparing for coding interviews.
