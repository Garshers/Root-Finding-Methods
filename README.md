## Approximate Solving of Non-Linear Equations

This project contains implementations of numerical methods used to find the roots of non-linear equations. The following methods are included:

- **Bisection Method**
- **Secant Method**
- **Regula Falsi Method**

These methods are iterative techniques that approximate the root of a given function. While they all aim to find the same solution, each method uses a different approach for narrowing down the possible values of the root.

### Bisection Method
The Bisection Method is a bracketing method that divides the interval containing the root into two equal parts. At each step, it evaluates which subinterval contains the root based on the sign of the function at the endpoints of the interval. This process continues until the root is approximated to the desired accuracy.

### Secant Method
The Secant Method is a non-bracketing method that approximates the root by using two initial guesses. It constructs a secant line between these two points and uses the intersection of this line with the x-axis as the next approximation of the root. The method iterates, refining the guesses at each step.

### Regula Falsi Method
The Regula Falsi Method, or False Position Method, is similar to the Bisection Method, but instead of halving the interval, it uses the intersection of a straight line connecting the function values at the endpoints to estimate the root. It continues to narrow down the interval based on this approximation.

### Performance Comparison
A performance comparison is made between the three methods by running each method multiple times. The following metrics are recorded:

- Solving time
- Number of iterations
- Approximated root value

### Observations
The efficiency of the methods varies depending on the problem and the initial conditions. The Secant Method typically requires fewer iterations and less time to converge, while the Bisection Method is more straightforward but may need more iterations. The Regula Falsi Method often offers a balance between the two.

### Average Performance
The average solving time and number of iterations for each method are calculated over multiple runs to provide insights into the relative efficiency of each approach.

### Conclusion
Based on the experiments, the **Secant Method** is the most efficient, generally requiring fewer iterations and less solving time. The **Bisection Method** is slower but offers more reliability in convergence. The **Regula Falsi Method** provides a compromise between the other two methods. The overall performance depends on the specific problem and the nature of the function being analyzed.

## Requirements

- A MATLAB environment or equivalent software capable of running MATLAB code.

## License

This project is open-source and licensed under the MIT License.
"# Root-Finding-Methods" 
