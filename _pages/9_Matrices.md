

# Matrices

In this week's tutorial, we will use the techniques from the previous lecture to complete a mini-project. You should save any files you work on as spreadsheets, so you can refer back to them later.

```{exercise}
:label: mats-ex1

    $A = \begin{pmatrix} 1 & 1 & 3\\ 6 & 1 & 2\\ 2 & 4 & 5 \end{pmatrix}$

    \vspace{0.3cm}
    Let $A'$ be the matrix created by reflecting the matrix $A$ from top to bottom, and let $B$ be the matrix made from three copies of the first row of $A$.
    
&emsp;(a) What is $\operatorname{det}A$?
&emsp;(b) What is $\operatorname{det}A'$?
&emsp;(c) What is $\operatorname{det}B$?
         
```

```{exercise}
:label: mats-ex2

 $C = \begin{pmatrix} 3 & -1 & 4\\
     1 & 5 & 2\\
    -2 & -1 & 5
     \end{pmatrix}$
     
    \vspace{0.3cm}
     
&emsp;(a) What is $\operatorname{det}C$?
&emsp;(b) What is $\operatorname{det}C^{\mathsf{T}}$?
&emsp;(c) What is $\operatorname{det}(C + \begin{pmatrix} 0 & 0 & 0\\
     0 & 0 & 0\\
    2 & 1 & -5
     \end{pmatrix})$?
&emsp;(d) What is $\operatorname{det}(C - \begin{pmatrix} 0 & 0 & 0\\
     0 & 0 & 0\\
    2 & 1 & -5
     \end{pmatrix})$?
&emsp;(e) What is $\operatorname{det}(C - \begin{pmatrix} 0 & -1 & 4\\
     1 & 0 & 2\\
    -2 & -1 & 0
     \end{pmatrix})$?

```

```{exercise}
:label: mats-ex3

(a) Open the link below and observe that Wolfram|Alpha can calulate the determinant of a matrix.

[Wolfram|Alpha - Matrix Determinant example](https://www.wolframalpha.com/input?i=determinant+of+%7B%7B2%2C1%7D%2C%7B1%2C3%7D%7D
)

(b) Note that for a $2 times 2$ matrix, the value of the determinant is equal to the area of a parallelogram made using the two vectors. Change the values in the matrix to see how this affects the shape, and the determinant.

(c) Recall that swapping two rows or columns in a matrix makes the determinant change sign. Try this with the matrix and observe what happens to the parallelogram. Why might this be a negative value?

(c) Change the matrix so it is now a $3 \times 3$ matrix. (Note how the matrix is written in Wolfram language, and modify this to add an extra entry in each row, and a third row).

```