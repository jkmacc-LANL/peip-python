# PEIP-Python

Python code for examples and exercises for the 3rd edition of Parameter
Estimation and Inverse Problems.

## Differences between MATLAB and Python/NumPy/Jupyter

* In MATLAB, documentation on a function is obtained with `help function_name`.
  In Jupyter and IPython, help is obtained with `function_name?`.
* In MATLAB, array indices begin with 1.  In Python and NumPy, indices begin with 0.
* In MATLAB, vectors are matrices with their second dimension of length 1.
  In NumPy, vectors have no second dimension.
* In MATLAB, element-by-element operations are explicit with a `.` dot before the symbol.
  In NumPy, element-by-element is the default.  Futher, element-by-element operations can
  occur between different sized arrays through ["broadcasting"](https://docs.scipy.org/doc/numpy/user/basics.broadcasting.html), whereby
  array dimensions are matched and the operation is implicitly expanded to all
  corresponding elements.
* In MATLAB, the array transpose is obtained with an apostrophe `'` after the matrix.
  In NumPy, it is obtained with the `.T` method on the array.

For other differences, please see [NumPy for MATLAB users](https://docs.scipy.org/doc/numpy/user/numpy-for-matlab-users.html).