#### Pseudocode: Solution of system of equations
```
FUNCTION Solution (A,b):
  Create Augmented matrix : k=[A|b]
  Reduce in Row Reduced Echleon form
  Rank = no. of non zero rows RREF
  IF Rank(k)= Rank (A):
  print (System is inconsistent)
  ELSE IF:
  Solve using back substitution
END FUNCTION
```
# Python Fundamentals
-
