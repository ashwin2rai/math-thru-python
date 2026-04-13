# math-thru-python

# Introduction

This repo adds to Mathematical Notation: A Guide for Engineers and Scientists by Professor Edward Scheinerman by including code for notations, to make it easier to understant the concept behing standard mathematical notations. 

These set of notebooks serve two purposes

1. Introduces and expands on commonly used mathematical symbols and notations
2. Shows the symbol in code form using Python

The motivation behind (1) is to assist people that are trying to slog through mathematics literature and need  a handy guide to look up notations and the associated meaning behind it. It is commonly believed that mathematical notations help mathematicians and other trained professionals to pack a lot of information in a compact form, thus aiding in effective communication, but the same notations can be a barrier for individuals that are not familiar with the lexicon. This notebook can then be used to learn or recall the meaning behind symbols used to communicate mathematical concepts.

The motivation behind (2) is to help individuals grasp the concept behind these notations by mapping it into code. It is often felt by programmers and developers that a 10 minute explanation behind a concept can be grasped in 1 minute by simply looking at the accompanying code that executes the concept. The same philosophy is used in this notebook where-in a notation is associated with a block of code to fully comprehend the concept behind the notation.  

Python is an appropriate programming language for this endevour since Pythonic syntax commonly has a 1:1 mapping with it's corresponding mathematical syntax. 

## Notes

1. The notebooks are largely self-contained, i.e, if you see a symbol there will be an explanation about it at some point in the notebook.
    - Most often there will be links to the cell where the symbols are explained
    - If the symbols are not explained in this notebook, a reference to the appropriate notebook will be provided
    
    
2. **Github does a poor job of rendering these notebooks**. The online render of these notebooks are missing links, symbols, and notations are badly formatted. It is advised that you clone a local copy (or download the notebook) and open it locally, or refer to the PDFs.

# Essential list of notations

If you do not have time to peruse all the content in this repository, below is a cheat sheet of items worth reading first to gain basic familiarity with the most widely used notations, in order. It is written in Subtopic - Main Topic - Notebook format.

Collections/Numbers

1. Membership - Sets - Collections
2. Real set - Sets - Collections
3. Integer set - Sets - Collections
4. Set builder notation - Sets - Collections
5. Intervals - Subset of the Reals - Numbers
6. Subset - Sets - Collections
7. Superset - Sets - Collections
8. Union - Sets - Collections
9. Intersection - Sets - Collections
10. Cartesian product - Sets - Collections
11. Infimum, Supremum - Sets - Collections
12. Introduction - Lists or n-tuples - Collections
13. Big Sum - Aggregation symbols - Collections
14. Big Product - Aggregation symbols - Collections

Logic

1. For all - Quantifiers - Logic
2. There exists - Quantifiers - Logic
3. Combining quantifiers - Quantifiers - Logic
4. Implies - Proof Symbols - Logic
5. If and only if - Proof Symbols - Logic

Numbers

1. Absolute value - Real numbers - Numbers
2. Defined - Real numbers - Numbers
3. Identically equal to - Real numbers - Numbers
4. Higher dimensional spaces - Subset of the Reals - Numbers
5. Decorations - Subset of the Reals - Numbers
6. Complex set - Complex numbers - Numbers

Functions

1. Set Map - Fundamentals - Functions
2. Value Notation - Fundamentals - Functions
3. Dot Notation - Fundamentals - Functions
4. Piecewise Notation - Fundamentals - Functions
5. Composition of Functions - Fundamentals - Functions
6. Operator / Transform - Fundamentals - Functions
7. Function Exponentiation - Fundamentals - Functions
8. Arg Min and Arg Max - Miscellany - Functions

Linear Algebra

1. Magnitude or Norm of a vector - Vectors - Linear_algebra
2. Dot (inner) product - Vectors - Linear_algebra
3. Orthogonality - Vectors - Linear_algebra
4. Matrix multiplication - Matrices - Linear_algebra
5. Transpose - Matrices - Linear_algebra
6. Determinant - Matrices - Linear_algebra
7. Eigenvalues - Matrices - Linear_algebra

Geometry

1. Angles - Fundamentals - Geometry
2. Parallel - Fundamentals - Geometry
3. Perpendicular - Fundamentals - Geometry
4. Cartesian coordinates - Coordinates - Geometry
5. Polar coordinates - Coordinates - Geometry

Calculus

1. Limit of a Function - Limits - Calculus
2. Derivative Notation - Derivatives (Single Variable) - Calculus
3. Partial Derivatives - Partial Derivatives (Scalar-Valued) - Calculus
4. Gradient - Partial Derivatives (Scalar-Valued) - Calculus
5. Definite Integral - Integration - Calculus
6. Jacobian - Derivatives (Vector-Valued) - Calculus

Probability and Statistics

1. Expected Value - Probability - Probability_Stats
2. Variance - Probability - Probability_Stats
3. Standard Deviation - Probability - Probability_Stats
4. Probability Mass Function (PMF) - Distributions - Probability_Stats
5. Cumulative Distribution Function (CDF) - Distributions - Probability_Stats
6. Probability Density Function (PDF) - Distributions - Probability_Stats
7. Estimator - Statistics - Probability_Stats

Approximations

1. Approximate Equality - Approximate Equality of Numbers - Approximations
2. Asymptotic To - Asymptotic Relations - Approximations
3. Big O - Big-Oh Notation and Its Relatives - Approximations


# References

1. The excellent - Mathematical Notation: A Guide for Engineers and Scientists by Professor Edward Scheinerman;
    - [Copy @ Amazon](https://www.amazon.ca/Mathematical-Notation-Guide-Engineers-Scientists/dp/1466230525)
    - [Copy @ Google Ebooks](https://books.google.ca/books/about/Mathematical_Notation.html?id=fJbMygAACAAJ)
3. https://en.wikipedia.org/wiki/Glossary_of_mathematical_symbols
4. https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols
5. http://www-cs-students.stanford.edu/~csilvers/proof/node1.html#intro
6. https://math.libretexts.org/Bookshelves/Mathematical_Logic_and_Proof/Book%3A_Book_of_Proof_(Hammack)/07%3A_Proving_Non-Conditional_Statements/7.01%3A_If-and-Only-If_Proof
