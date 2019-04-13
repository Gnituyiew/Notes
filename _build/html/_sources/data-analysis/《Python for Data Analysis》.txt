《Python for Data Analysis》
==========================

重要的Python库
------------

NumPy
~~~~~

NumPy, short for Numerical Python, is the foundational package for scientific com-
puting in Python. The majority of this book will be based on NumPy and libraries built
on top of NumPy. It provides, among other things:

* A fast and efficient multidimensional array object ndarray

* Functions for performing element-wise computations with arrays or mathematical operations between arrays

* Tools for reading and writing array-based data sets to disk

* Linear algebra operations, Fourier transform, and random number generation

* Tools for integrating connecting C, C++, and Fortran code to Python

Beyond the fast array-processing capabilities that NumPy adds to Python, one of its
primary purposes with regards to data analysis is as the primary container for data to
be passed between algorithms. For numerical data, NumPy arrays are a much more
efficient way of storing and manipulating data than the other built-in Python data
structures. Also, libraries written in a lower-level language, such as C or Fortran, can
operate on the data stored in a NumPy array without copying any data.
