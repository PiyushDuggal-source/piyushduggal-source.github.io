---
title: "Matrix: Python version!"
date: 2023-11-18 00:00:00 +0530
categories: [programming, python, tech]
tags: [python, iitmbs, iitm, matrix]
---

# Matrix: Python version! 🐍

![visitors](https://visitor-badge.laobi.icu/badge?page_id=piyushduggal-source.matrix-python-version)

_"What is the Matrix? It is the world that has been pulled over your eyes to blind you from the truth."_ - Morpheus, The Matrix (1999)

## Introduction to Matrices ⚔️

#### What is Matrix?

<div class="bg-blue-100" style="font-size: 20px">
  Is it like The <span class="font-mono">Keanu Reeves</span> <img src="/assets/img/KeanuReeves.jpeg" alt="Keanu Reeves" style="height: 25px; margin: 0 5px; border-radius: 2px;"> movie, "The Matrix"? Where he comes in a black suit and black glasses? Stopping all the bullets? 😵
</div>

<!-- <img src="/assets/img/python-matrix.png" alt="The Matrix" style="height: 300px; width:100%; object-fit: cover; margin: 0 5px;"> -->
<img src="/assets/img/matrix-movie.jpg" alt="The Matrix" style="border-radius: 10px"/>

_Keanu Reeves (as Neo) stopping bullets_ 🗿

**NO! Right?**
Its not like the movie...

Well, In mathematics, a matrix is a `two-dimensional` array of numbers, symbols, or expressions arranged in `rows` and `columns`. It holds significance across diverse fields like computer graphics, physics, machine learning, and more.

Same in Python!

### Creating a Matrix in Python

Let's create a simple 3x3 (3 `rows`, 3 `columns`) matrix using Python's built-in lists:

```python
# Creating a 2x3 matrix
matrix = [
  [1, 2, 3], # first row
  [4, 5, 6]  # second row
  [7, 8, 9]  # third row
]
print("Matrix: ")
for row in matrix:
    print(row)
```

<img src="/assets/img/output.png" alt="Matrix image" style="height: 300px; border-radius: 10px">

_This image shows a 3x3 matrix, with the corresponding `row position` and `column position`._

That's it! 🎉 Congratulations! You just created a matrix in Python.

Well... We are going good so far. Let's see if we can make it more interesting 🎉

### Matrix Operations

We can use various matrix operations in Python. For example, we can `add` two matrices together:

Let's start with some simple examples:

##### Addition

```python
# Define matrices
matrix1 = [[1, 2, 3],
           [4, 5, 6],
           [7, 8, 9]]

matrix2 = [[9, 8, 7],
           [6, 5, 4],
           [3, 2, 1]]

# Initialize a result matrix with zeros of the same size
result = [[0, 0, 0],
          [0, 0, 0],
          [0, 0, 0]]

# Perform matrix addition
for i in range(len(matrix1)):
    for j in range(len(matrix1[0])):
        result[i][j] = matrix1[i][j] + matrix2[i][j]

# Displaying the result
print("Matrix Addition Result:")
for row in result:
    print(row)

```

Wait wait wait..., do not panic that we are using `nested` for loops. (we have to 💀)

<div style="display: flex; align-items: center">
But Don't worry, I'll explain everything in detail ! <img src="https://tenor.com/en-GB/view/the-office-michael-scott-the-office-memes-thank-you-the-office-steve-carell-gif-4747908160646773958.gif" alt="GIF from The Office" style="height: 50px; margin: 0 5px;">
</div>

- `matrix1` and `matrix2` are two matrices defined using nested lists.
- `result` is initialized as a matrix filled with zeros of the same size as `matrix1` and `matrix2`.
- On line number `16` and `17`, `for` loops are used to iterate over the rows and columns of `matrix1` and `matrix2`.
- On line number `18`, `result[i][j]` is used to store the sum of the elements in `matrix1[i][j]` and `matrix2[i][j]`.
- Well, you know the `print` part.

Cool, we are done! 🎉 Let's see what else we can do with matrices!

##### Multiplication

```python
# Define matrices
matrix1 = [[1, 2],
           [3, 4]]

matrix2 = [[5, 6],
           [7, 8]]

# Initialize a result matrix with zeros
result = [[0, 0],
          [0, 0]]

# Perform matrix multiplication
for i in range(len(matrix1)):
    for j in range(len(matrix2[0])):
        for k in range(len(matrix2)):
            result[i][j] += matrix1[i][k] * matrix2[k][j]

# Displaying the result
print("Matrix Multiplication Result:")
for row in result:
    print(row)
```

<div style="display: flex; align-items: center">
Again <code style="margin: 0 5px" class="language-plaintext highlighter-rouge">nested loops</code> <img src="https://tenor.com/en-GB/view/the-office-no-angry-steve-carell-michael-scott-gif-5606969.gif" alt="GIF from The Office" style="height: 70px; margin: 0 5px; border-radius: 5px;">.
</div>

##### Let me explain everything:

- `matrix1` and `matrix2` are two matrices defined using nested lists.
- `result` is initialized as a matrix filled with zeros of the same size as `matrix1` and `matrix2`.
- On line number `13` Three nested loops are used to perform matrix multiplication. The loops iterate through the elements of the matrices and calculate the dot product to find the resulting `matrix`.
- Again, you know the `print` part.

These examples demonstrate basic matrix addition and multiplication using Python's built-in lists, without using NumPy.

## Where Matrices are Used in Python:

1. **Data Science and Machine Learning:**

   - Data representation and linear algebra operations in algorithms like regression, classification, and dimensionality reduction.

2. **Image Processing and Computer Vision:**

   - Representing images as matrices of pixels and using matrices in operations like convolutions in CNNs.

3. **Graph Theory and Network Analysis:**

   - Matrices represent connections in graphs and are crucial in algorithms like PageRank.

4. **Engineering and Physics:**

   - Modeling physical systems, solving differential equations, and finite element analysis.

5. **Optimization and Operations Research:**

   - Matrices are fundamental in solving optimization problems, especially in linear programming.

6. **Financial Analysis and Economics:**

   - Portfolio optimization, risk management, and input-output analysis in economics.

7. **Game Development:**
   - Using matrices for transformations (e.g., translations, rotations) in 2D/3D game development.

Python, especially with libraries like NumPy, SciPy, and Matplotlib, facilitates efficient manipulation and operations with matrices, making it versatile across various fields requiring matrix computations.

### Conclusion

<div class="bg-blue-100" style="font-size: 20px">
  I hope this article helped you understand the basics of matrices in Python. 🎉
</div>

Thanks very much! <br/>
Happy hacking!

by [@piyushduggal-source](https://github.com/piyushduggal-source) (_mr_unchained_)

_Note: I did not use ChatGPT, kasam se.._
