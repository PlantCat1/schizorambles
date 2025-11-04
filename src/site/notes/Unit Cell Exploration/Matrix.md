---
{"dg-publish":true,"permalink":"/unit-cell-exploration/matrix/"}
---

A matrix is a rectangular array of mathematical objects arranged in rows and columns.
A single one of these objects is called an element or entry.
Numbers are most commonly used.
# Parts
## Rows
## Columns
## Entries
# Notation
Matrices are commonly written in square brackets or parentheses.
The entire matrix is often symbolized using upper-case letters. Ex: $A$
Entries are represented using the corresponding lowercase.  With two subscripts representing the indices of that element. ex: $a_{mn}$
# Matrix Size/Dimension
Matrix Sizes/Dimensions describe a matrix's size by stating the number of rows  ($m$) and columns ($n$).
One method to represent this is $m \times n$. Out loud its read as a "$m$-by-$n$ matrix".
A more formal method is $A \in \mathbb{R}^{m \times n}$. This denotes the matrix size, but that the entries belong to the [[Wiki/Real Numbers\|real numbers]], which can be replaced with any [[Wiki/common number set\|common number set]].
## Example
$$
\mathbf{A} = 
\begin{bmatrix}  
a_{11} & a_{12} & a_{13} \\  
a_{21} & a_{22} & a_{23} \\  
\end{bmatrix}
$$
$m=2$, $n=3$.
"2 by 3 matrix"
$2 \times 3$
$A \in \mathbb{R}^{2 \times 3}$
# Types of Matrices by Size/Shape
## Singleton Matrix
A matrix that has only entry and therefore one row and one column. Its size is $1 \times 1$
$$
\mathbf{A} = 
\begin{bmatrix}  
a_{11} \\  
\end{bmatrix}
$$
## Row Matrix
A matrix that has only one row and any number of columns. Its size is 
$$
\mathbf{A} = 
\begin{bmatrix}  
a_{11} & a_{12} & \dots & a_{1n} \\  
\end{bmatrix}
$$
## Column Matrix
A matrix that has only one column and any number of rows.
$$
\mathbf{A} = 
\begin{bmatrix}  
a_{11} \\
a_{21} \\
\dots \\
a_{m1} \\
\end{bmatrix}
$$
## Square Matrix
A matrix with the same number of rows and columns
These can be called $n \times n$ matrices.
$$
\mathbf{A} = 
\begin{bmatrix}  
a_{11} & a_{12} & \dots & a_{1n} \\  
a_{21} & a_{22} & \dots & a_{2n} \\  
\vdots & \vdots & \ddots & \vdots \\  
a_{m1} & a_{m2} & \dots & a_{mn}  
\end{bmatrix} \quad \text{where } n = m
$$
# Types of Matrices by Entries
## Zero Matrix
A matrix in which every element is 0. It can be of any size $m \times n$.
Also known as a null matrix.
$$
\mathbf{O_{m \times n}} = 
\begin{bmatrix}  
0 & 0 & \dots & 0 \\  
0 & 0 & \dots & 0 \\  
\vdots & \vdots & \ddots & \vdots \\  
0 & 0 & \dots & 0  
\end{bmatrix}
$$
# Other Types
## [[Unit Cell Exploration/Configuration Matrix\|Configuration Matrix]]