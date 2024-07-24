# Python for Linear Algebra
## Pseudocode for Linear Algebra
### Definition: Pseudocode is a way to describe algorithms in a structured but plain language. 
### Matrix Sum
#### Mathematical Procedure:
      C[i][j] = A[i][j] + B[i][j]
#### Example
$$ A = \begin{bmatrix} 1 & 2 \\ 
3 & 4 \end{bmatrix} ,
 B = \begin{bmatrix} 5 & 6 \\ 
7 & 8 \end{bmatrix} Ans: 
C = A + B = \begin{bmatrix} 1+5 & 2+6 \\ 
3+7 & 4+8 \end{bmatrix} = \begin{bmatrix} 6 & 8 \\ 
10 & 12 \end{bmatrix} $$

#### Pseudocode
````
FUNCTION matrix_sum(A, B):
    Get the number of rows and columns in matrix A
    Create an empty matrix C with the same dimensions
    FOR each row i:
        FOR each column j:
            Set C[i][j] to the sum of A[i][j] and B[i][j]
    RETURN the matrix C
END FUNCTION
````
### Matrix Difference
#### Mathematical Procedure:
      C[i][j] = A[i][j] - B[i][j]
#### Example
$$ A = \begin{bmatrix} 9 & 8 \\ 
7 & 6 \end{bmatrix} ,
 B = \begin{bmatrix} 1 & 2 \\ 
3 & 4 \end{bmatrix} Ans: 
C = A - B = \begin{bmatrix} 9-1 & 8-2 \\ 
7-3 & 6-4 \end{bmatrix} = \begin{bmatrix} 8 & 6 \\ 
4 & 2  \end{bmatrix} $$

#### Pseudocode
````
FUNCTION matrix_difference(A, B):
    Get the number of rows and columns in matrix A
    Create an empty matrix C with the same dimensions
    FOR each row i:
        FOR each column j:
            Set C[i][j] to the difference of A[i][j] and B[i][j]
    RETURN the matrix C
END FUNCTION
````




