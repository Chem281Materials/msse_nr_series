# Numerical Evaluation of a Series

Perform all your calculations for this problem in single precision.

Consider the infinite series:

$$S = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \frac{1}{5} - \frac{1}{6} \cdots$$

This series converges analytically to a value of $\ln{(2)}$.

Write C++ code that computes the approximate value of $S$ by summing a finite number of terms in this series; we will denote this finite number of terms `N`.
Try two difference approaches: (a) one in which you sum the first `N` terms in the series from left to right, and (b) one in which you sum the first `N` terms in the series from right to left.
For both approaches, compute estimates of the value of $S$ for `N` $= 10^{3}$, $10^{4}$, $10^{5}$, $10^{6}$, $10^{7}$, $10^{8}$, and $10^{9}$.
Also compute the absolute value of the error in all of your estimates of $S$, relative to the analytic value.

Report your results at the end of this `README.md` file.

In addition, plot the absolute values of the error for each method versus `N` on a $\log_{10}-\log_{10}$ scale.
You are not required to write C++ code to create the plot; you may create it externally.
Include the plot in this repository and explain the reasons for any differences in the results of the two methods.

## Answer
