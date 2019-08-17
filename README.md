# OpenCv
OpenCv 

Determinant of Matrix.

A = a b
    c d
  |A| = (ad - bc) for 2 X 2 Matrix

if A is 3 X 3 Matrix then 
    a b c
A = d e f
    g h i
    
|A| = a(ei - hf) - b(di - gf) + c(dh - ge)

Note :- Pattern is +,-,+,-...

EigenValues and Eigen Vectors.

EigenValues :-

det(A - λI) = 0 // where λ is EigenValues and I is Identity Matrix

EigenVectors :-

For each eigenvalues λ we have 
    (A - λI)x = 0 // where x is the eigenvectors of each eigenvalues λ
