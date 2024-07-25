# Python for Linear Algebra
## Pseudocode for Linear Algebra
### Definition: Pseudocode is a way to describe algorithms in a structured but plain language. 
### Matrix Sum
#### Mathematical Procedure:
      C[i][j] = A[i][j] + B[i][j]
#### Example
$$A = \begin{bmatrix} 1 & 2 \\ 
3 & 4 \end{bmatrix} ,
 B = \begin{bmatrix} 5 & 6 \\ 
7 & 8 \end{bmatrix}$$

Ans: 

$$C = A + B = \begin{bmatrix} 1+5 & 2+6 \\ 
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
3 & 4 \end{bmatrix} $$

Ans: 

$$C = A - B = \begin{bmatrix} 9-1 & 8-2 \\ 
7-3 & 6-4 \end{bmatrix} = \begin{bmatrix} 8 & 6 \\ 
4 & 2  \end{bmatrix}$$

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
### Matrix Product
#### Mathematical Procedure

$$ C[i][j] = \sum_{k} A[i][k] \cdot B[k][j] $$

#### Pseudocode
```
FUNCTION matrix_product(A, B):
    # Get the dimensions of A and B
    rows_A = number_of_rows(A)
    cols_A = number_of_columns(A)
    rows_B = number_of_rows(B)
    cols_B = number_of_columns(B)
    
    # Check if multiplication is possible
    IF cols_A != rows_B:
        RAISE Error("Incompatible matrix dimensions")
    
    # Initialize result matrix C
    C = create_matrix(rows_A, cols_B)
    
    # Calculate matrix product
    FOR each row i FROM 0 TO rows_A-1:
        FOR each column j FROM 0 TO cols_B-1:
            # Compute the sum for C[i][j]
            sum = 0
            FOR each k FROM 0 TO cols_A-1:
                sum = sum + A[i][k] * B[k][j]
            C[i][j] = sum
    
    RETURN C
END FUNCTION
```
```
FUNCTION matrix_product(A, B):
    Get the number of rows and columns in matrix A
    Get the number of columns in matrix B
    Create an empty matrix C with dimensions rows_A x cols_B
    FOR each row i in A:
        FOR each column j in B:
            Initialize C[i][j] to 0
            FOR each element k in the common dimension:
                Add the product of A[i][k] and B[k][j] to C[i][j]
    RETURN the matrix C
END FUNCTION
```
### Determinant
#### Mathematical Procedure:
$$
\text{det}(A) = A[0][0] \cdot A[1][1] - A[0][1] \cdot A[1][0]
$$
### 


