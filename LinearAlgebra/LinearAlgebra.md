# Linear Algebra



- Scalars : {$x$ | $x \in \real$  }.Scalar can be $+$ or $- $

- Vector  $\vec{o}$  is a *basis vector* ,{$\vec{o}$ | $\vec{o} \in \real$  }

- Vector Addition and Multiplication

- Vector is rooted at origin 

- Combination of addition and multiplication on  a pair of scalar vectors can yield any vector in that dimension and is called Span those vectors
  - Set of vectors : ( $\vec{v}$ , $\vec{w}$ ) 
  - Scalar vectors :  $a\vec{v}$ , $b\vec{w}$ 
  - Linear Combination   :   $a\vec{v} + b\vec{w}$    = Span of    $\vec{v}$ and $\vec{w}$ 
  - **Exceptions** - 
    -  when  $\vec{v}$ or  $\vec{w}$ are in same line of vector then the only direction linear combination can move is forward or backward. 
    - When both vectors are at origin.









---

#### Understanding LT in Linear Transformation

##### T in Linear Transformation 

​	**Transformation is a fancy word for a function** that takes an input and spits outs an output.		

Or 

​	Which takes in a vector and spits out another vector. 

Transformation is used with respect to movement. Transforming one vector to another vector



##### L in Linear Transformation

A transformation is linear if  and only if

- All lines remains lines  OR Grid Lines are always parallel  and evenly spaced OR Transformations are not curved.
- Origin does not move/is always fixed.



##### Representing Linear Transformation Numerically



 In 2 Dimensions,linear Transformation can be represented using a linear combination of  $\hat{i}$ and $\hat{j}$ , which are basis of two vectors.

 
$$
x\hat{i} + y\hat{j} = \hat{v}
$$


where $\hat{v}$ is the resultant vector. 



A transformation of one  these vectors can be  $h(\hat{i}) = a\hat{i} = \hat{k}$

Similarly,  $h(\hat{j}) = b\hat{i} = \hat{l}$ 

and linear combination of these two new vectors are  $\hat{k} + \hat{l} = \hat{m} = c\hat{v}$

Hence 
$$
h(\hat{i}) = a\hat{i} = \hat{k} \\
h(\hat{j}) = b\hat{i} = \hat{l}\\ hence \\
\hat{k} + \hat{l} = \hat{m} \\ OR \\
x(a\hat{i}) + y(b\hat{j}) = c\hat{v} \\ OR \\
xa(\hat{i}) + yb(\hat{j}) = c\hat{v} \\OR \\
s(\hat{i}) + s'(\hat{j}) = s''\hat{v}
$$
where $s,s'$ and $s''$ are some scalar value. 

Hence Linear Transformation is some linear combination of scalar and vectors in that dimension.

At the end should know : How Statistical Problem becomes a Linear Algebra Problem