# Linear Algebra



- Scalars : {$x$ | $x \in \real$  }.Scalar can be $+$ or $- $

- Vector  $\vec{o}$  is a *basis vector* ,{$\vec{o}$ | $\vec{o} \in \real$  }

- Vector Addition and Multiplication

- Vector is rooted at origin 

- Combination of addition and multiplication on  a pair of scalar vectors can yield any vector in that dimension and is called Span those vectors
  - Set of vectors : ( $\vec{v}$ , $\vec{w}$ ) 
  
  - Scalar vectors :  $a\vec{v}$ , $b\vec{w}$ 
  
  - **Linear Combination**   :     
    $$
    a\vec{v} + b\vec{w} \tag{1}
    $$
    
  
    - where equation 1 is Span of  $\vec{v}$ and $\vec{w}$ 
  
  - **Exceptions** - 
    
    1. When  $\vec{v}$ or  $\vec{w}$ are in same line of vector then the only direction linear combination can move is forward or backward.  This mean one of the vector is scalar multiple of other.
    
    2. When both vectors are at origin.



---

#### Basis Vector

Basis in any dimension space is divided into  Standard Basis and Non-Standard Basis.

Linear Combination of basis vectors yield any vector coordinates in that dimension space also known as **span**.

---

#### Understanding L,T in Linear Transformation

##### T in Linear Transformation

​	**Transformation is a fancy word for a function** that takes an input and spits outs an output.		

Or 

​	Which takes in a vector and spits out another vector. 

Transformation is used with respect to movement. Transforming one vector to another vector

##### L in Linear Transformation

A transformation is linear if  and only if

- All lines remains lines  OR Grid lines are always parallel  and evenly spaced OR Transformations are not curved.
- Origin does not move/is always fixed.

##### Representing Linear Transformation Numerically

 In 2 Dimensions,linear transformation can be represented using a linear combination of  $\hat{i}$ and $\hat{j}$ , which are basis of two vectors.
$$
x\hat{i} + y\hat{j} = \hat{v} \tag{2}
$$
where $\hat{v}$ is the resultant vector. 

A transformation of these vectors can be 
$$
h(\hat{i}) = a\hat{i} = \hat{k} \tag{3}
$$
$$
h(\hat{j}) = b\hat{i} = \hat{l} \tag{4}
$$
and linear combination of these two new vectors can be  
$$
\hat{k} + \hat{l} = \hat{m} = c\hat{u} \tag{4.1}
$$


Hence 
$$
\hat{k} + \hat{l} = \hat{m} =c\hat{v}
$$
$$
x(a\hat{i}) + y(b\hat{j}) = c\hat{v}  \tag{5}
$$

$$
xa(\hat{i}) + yb(\hat{j}) = c\hat{v} \tag{6}
$$

$$
w(\hat{i}) + t(\hat{j}) = f\hat{v} \tag{7}
$$

1. Where $w,t$ and $f$ are some scalar value, they may or may not be same. 

2. $a\hat{i}$  and   $b\hat{j}$ are transformed vector $\hat{k}$ and $\hat{l}$ which form the  new basis of new transformed space  
3. Hence all linear transformation can be expressed as equation $(2)$.

Hence, Linear Transformation of 2 vectors is some linear combination of scalar and vectors in 2-D dimension can be written as 
$$
x\hat{i} + y\hat{j} = \hat{v} \\
x \begin{bmatrix} c \\ e\end{bmatrix} + y\begin{bmatrix} d \\ f\end{bmatrix} = \hat{v}\\
 \begin{bmatrix}
c & d \\
e & f
\end{bmatrix} \begin{bmatrix} x \\ y\end{bmatrix} = \hat{v}  \\
$$


![](/home/abhinav/Pictures/HOwdescribeNumercally3.png)

> **Linear Algebra is a way to move around in n-dimension space while keeping grid-line parallel and evenly spaced while origin remains fixed.** 

---



Question : Equation $(2)$  exit. If $(3)$ and $(4)$ is known $(4.1)$ can be deduced 







---

At the end should know : How Statistical Problem becomes a Linear Algebra Problem







---





Composition Vector - Matrix Multiplication of 2 Matrices - Matrix Multiplication of Matrices  is same as Applying two transformations


$$
x\hat{i} + y\hat{j} = \hat{v} \\
x \begin{bmatrix} c \\ e\end{bmatrix} + y\begin{bmatrix} d \\ f\end{bmatrix} = \hat{v}\\
 \begin{bmatrix}
c & d \\
e & f
\end{bmatrix}
\begin{bmatrix} x & g \\ y & h \end{bmatrix}  = \hat{v}  \\
$$
