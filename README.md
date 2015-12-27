
#Introduction

This second programming assignment will require me to write an R function that is able to cache potentially time-consuming computations. For example, taking the mean of a numeric vector is typically a fast operation. However, for a very long vector, it may take too long to compute the mean, especially if it has to be computed repeatedly (e.g. in a loop). If the contents of a vector are not changing, it may make sense to cache the value of the mean so that when we need it again, it can be looked up in the cache rather than recomputed. In this Programming Assignment I will take advantage of the scoping rules of the R language and how they can be manipulated to preserve state inside of an R object.




#Write the following functions:

makeCacheMatrix: This function creates a special "matrix" object that can cache its inverse.
cacheSolve: This function computes the inverse of the special "matrix" returned by makeCacheMatrix above. If the inverse has already been calculated (and the matrix has not changed), then cacheSolve should retrieve the inverse from the cache.
Computing the inverse of a square matrix can be done with the solve function in R. For example, if X is a square invertible matrix, then solve(X) returns its inverse.

For this assignment, assume that the matrix supplied is always invertible.

In order to complete this assignment, you must do the following:

Fork the GitHub repository containing the stub R files at https://github.com/rdpeng/ProgrammingAssignment2 to create a copy under your own account.
Clone your forked GitHub repository to your computer so that you can edit the files locally on your own machine.
Edit the R file contained in the git repository and place your solution in that file (please do not rename the file).
Commit your completed R file into YOUR git repository and push your git branch to the GitHub repository under your account.
Submit to Coursera the URL to your GitHub repository that contains the completed R code for the assignment.
#Grading

This assignment will be graded via peer assessment.
