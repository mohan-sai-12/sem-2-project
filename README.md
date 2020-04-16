# sem-2-project
SPARSE MATRIX
                                                    Sparse Matrix Implementation
Description: 
                  Implement a sparse matrix in which any or most of the entries are zero. Because allocating memory space for all entries of the matrix will be wasteful we intend to allocate memory space only for nonzero entries.


Modules:
(a) Represent a sparse matrix as a doubly linked circular or any other data structure which you think is useful.  
(b) Write a program to perform the following operations: 
     (i) Read in inputs for the entries of a sparse matrix and form a suitable data structure.   
     (ii) Addition of two sparse matrices 
     (iii) Subtraction of two sparse matrices 
     (iv) Multiplication of two sparse matrices 
     (v) Print sparse matrix (in matrix form).

Hint: Each entry of a sparse matrix can be viewed as a structure of the form: 
Row-index,Column-index,Value Left pointer to pointer.
Row index points to the next row (i.e. down). Column-index points to the next column (i.e. right). Value points to the information of data type added. Left pointer points to the element towards the next left element. Right pointer points to the element towards the next up element.
