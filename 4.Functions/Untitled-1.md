# Module 4: Advanced Functions Assignments
## Lesson 4.1: Defining Functions
### Assignment 1: Fibonacci Sequence with Memoization

Define a recursive function to calculate the nth Fibonacci number using memoization. Test the function with different inputs.

### Assignment 2: Function with Nested Default Arguments

Define a function that takes two arguments, a and b, where b is a dictionary with a default value of an empty dictionary. The function should add a new key-value pair to the dictionary and return it. Test the function with different inputs.

### Assignment 3: Function with Variable Keyword Arguments

Define a function that takes a variable number of keyword arguments and returns a dictionary containing only those key-value pairs where the value is an integer. Test the function with different inputs.

### Assignment 4: Function with Callback

Define a function that takes another function as a callback and a list of integers. The function should apply the callback to each integer in the list and return a new list with the results. Test with different callback functions.

### Assignment 5: Function that Returns a Function

Define a function that returns another function. The returned function should take an integer and return its square. Test the returned function with different inputs.

### Assignment 6: Function with Decorators

Define a function that calculates the time taken to execute another function. Apply this decorator to a function that performs a complex calculation. Test the decorated function with different inputs.

### Assignment 7: Higher-Order Function for Filtering and Mapping

Define a higher-order function that takes two functions, a filter function and a map function, along with a list of integers. The higher-order function should first filter the integers using the filter function and then apply the map function to the filtered integers. Test with different filter and map functions.

### Assignment 8: Function Composition

Define a function that composes two functions, f and g, such that the result is f(g(x)). Test with different functions f and g.

### Assignment 9: Partial Function Application

Use the functools.partial function to create a new function that multiplies its input by 2. Test the new function with different inputs.

### Assignment 10: Function with Error Handling

Define a function that takes a list of integers and returns their average. The function should handle any errors that occur (e.g., empty list) and return None in such cases. Test with different inputs.

### Assignment 11: Function with Generators

Define a function that generates an infinite sequence of Fibonacci numbers. Test by printing the first 10 numbers in the sequence.

### Assignment 12: Currying

Define a curried function that takes three arguments, one at a time, and returns their product. Test the function by providing arguments one at a time.

### Assignment 13: Function with Context Manager

Define a function that uses a context manager to write a list of integers to a file. The function should handle any errors that occur during file operations. Test with different lists.

### Assignment 14: Function with Multiple Return Types

Define a function that takes a list of mixed data types (integers, strings, and floats) and returns three lists: one containing all the integers, one containing all the strings, and one containing all the floats. Test with different inputs.

### Assignment 15: Function with State

Define a function that maintains state between calls using a mutable default argument. The function should keep track of how many times it has been called. Test by calling the function multiple times.