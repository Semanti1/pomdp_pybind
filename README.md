To build:

cmake -S .

make

python test.py


Two POMDP problems are shown - Multi Object Search and Tiger. On running test.py, a test run for both problems are run. The C++ classes and functions implement the backend for structuring any POMDP problem. They are exposed to python through the example.cpp file. The functions specific to a problem are implemented in python as extensions of the backend. The algorithm to solve the POMDPs defined in python are implemented in C++. 
