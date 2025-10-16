# C-to-Python

Various examples and short exercises on bridging Python and compiled code

For the pi calculation using numpy, the result was around 2.7 seconds. This is in between the C version (1.21 s) and the python version without numpy (11.5 s). Using numpy yielded much more efficient code than using purely python loops because numpy actually uses vectorized routines using C code, and it uses more efficient random number generation as well.
  
