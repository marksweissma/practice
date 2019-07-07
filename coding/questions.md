## DS / Algs:
(no - non standard libraries numpy/pandas etc.)

For each solution, what are the space / time complexity. If you've made a trade off for one, how would you write the other. Is there a more optimal solution?

Consider a cyclic path of gas stations. Your gas tank has no max size and at each station
you add the entire amount of gas at the station. 
You begin at a station with no gas in tank and fill up.

Write code to answer the following two questions:

    1. Is it possible to complete the cycle
    2. If so, return a valid starting station

Window statistics

    Create a class for calculating window statistics from a stream.
    Object initializes with the size of the window (k)
    Object has a method to receive new values
    Object comes with `get_mean` method to calculate the current mean


Sampling

    Write a function to return a value from a stream with equal likelihood of any seen number returning.
    The stream cannot fit in memory 

Manipulation

    Transpose a 2d "matrix" (a list of lists input).
    Can you do it optimized for space (in place with only 1 free additional element for holding)



## Scikit-learn style Transformers
(can use numpy / pandas / other sk helpers that don't explicitly solve the problem):

Write your own (don't have to have all the options sklearn has):

    1. Standard Scaler
    2. One Hot Encoder
    3. Logistic Regression
    4. Decision Tree Regressor
