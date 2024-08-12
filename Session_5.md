# Session 5
## August 8th 2024
### Resources: https://sijuswamy.github.io/Computational-Linear-Algebra/module_2.html

### Hadamard Product
Element-wise multiplication

#### Application
Image processing and convolution neural network (masking)
icreasing brightness and contrast.
#### Properties of Hadamard Product
- Commutativity A.B = B.A
- Associativity (A.B).C = A.(B.C)
- Distributivity A.(B+C)=(A.B)+(A.C) (Multiplication is more complicated than addition)

Problems:
1) Find A.B and B.A if
$$A = \begin{bmatrix} 1 & 2 & 3 \\ 
3 & 4 & 5\\
6 & 7 & 8 \end{bmatrix} ,
 B = \begin{bmatrix} 1 & 0 & -1 \\ 
0 & 1 & 1 \\
3 & 1 & 0 \end{bmatrix}$$
#### Exam Viewpoint
- suppose A is an image and B is a marking matrix find the segmentation
- Mask A with B

####  Exam Questions:
Soln: Here A is 2X3 and M is 3X3. So we addd a zero row to A  **(zero padding)**

### Inner Product of Matrices
(always a scalar product) its is a measure
Element-wise multiplication and take sum.
**Note : sum of Hadamard product**
Let u=(u1,u2,u3)
v= (v1,v2,v3)
Then the inner product of u and v is defined as,
<u,v>  = u1v1+u2v2+u3v3
**Note : In image processing the aggregate effect of masking is the inner product of the image with the mask**

#### Example
Computer = operations are performed along columns

