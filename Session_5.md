# Session 5
## August 8th 2024


### Hadamard Product
Element-wise multiplication

### Application
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
