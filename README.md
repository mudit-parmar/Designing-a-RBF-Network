# Designing-a-RBF-Network
Designing of RBF NN based on Gaussian kernel functions with constant spread function and using all the points in the training set as centers of the RB functions

Createing an RBF Network to approximate the mapping defined by

    f(x1,x2)={  +1 if x1square + x2square <= 1
            
                -1 if x1square + x2square > 1
            
                over region -2 < x1 < 2 and -2 < x2 < 2
  
As a training set, use 441 randomly sampled data points defined as

    𝑥 = (𝑥i, 𝑥j)

Where

    𝑥i = −2 + 0.2 𝑖 𝑖 = 0,1,…,20

    𝑥j = −2 + 0.2 𝑗 𝑗 = 0,1,…,20


1. Carry out the design of RBF NN based on Gaussian kernel functions with constant spread function and using all
the points in the training set as centers of the RB functions. Compare the performance results (mean square
error) as you vary the spread parameter while keeping it the same for all kernel functions. Discuss your findings.


2. Perform the design of the RBF NN, using this time only 150 centers, choosing the centers using two approaches:

  a) Randomly select the centers from the input data.

  b) Use K-Means algorithm to find the centers. Keeping the spread parameter fix for all kernel functions. Compare the performance of this network to the one designed in
  part (1)
