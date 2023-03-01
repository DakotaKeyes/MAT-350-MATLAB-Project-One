# MAT-350-MATLAB-Project
Matrix Theory to Linear Equations & Transformations

Scenario
The communication network shows the sender transmitting 100 Mbps of data to router A and 50 Mbps of data to router C. From router A, there is an arrow labeled X₂ pointing to router C and an arrow labeled X₁ pointing to router B, and an arrow labeled X₂ pointing to router E. From router B, there is an arrow labeled X₅ pointing to router E and an arrow labeled X₃ pointing to the receiver. From router C, there is an arrow labeled X₃ pointing to router E and an arrow labeled X₅ pointing to router D. From router E, there is an arrow labeled X₄ pointing to router D. From router D, there is an arrow labeled X₂ pointing to router B and an arrow showing 120 Mbps of data being transmitted to the receiver.

You are employed as a network engineer and have been asked to analyze a communication network to determine the current data rates and ensure that the links aren’t at risk of “reaching capacity.” In the following figure of the network, the sender is transmitting data at a total rate of 100+50 = 150 megabits per second (Mbps). The data is transmitted from the sender to the receiver over a network of five different routers. These routers are labeled A, B, C, D, and E. The connections and data rates between the routers are labeled as x one, x two, x three, x four, and x five.

Directions
In this project, you will analyze the communication network and solve for the unknown data rates using a variety of techniques. The system can be modeled mathematically as a system of linear equations by writing an equation for each node/router in the network. Each of these equations can be written by noting that the sum of inputs must equal the sum of outputs.

To complete the project, work on the problems described below. As you complete each part, show your work and carefully describe how you arrive at your final answer. The methods and conclusions need to be clear when sharing your results with management. Any MATLAB code or MATLAB terminal outputs you generate should be provided in your submitted document to support your answers and work.

Develop a system of linear equations for the network by writing an equation for each router (A, B, C, D, and E). Make sure to write your final answer as Matrix A times vector x equals vector b where The matrix A is the five-by-five coefficient matrix, The vector x is the five-by-one vector of unknowns, and The vector b is a five-by-one vector of constants.

Use MATLAB to construct the augmented matrix An augmented matrix with the matrix A as the first entry and the vector b as the second entry and then perform row reduction using the rref() function. Write out your reduced matrix and identify the free and basic variables of the system.

Use MATLAB to compute the LU decomposition of The matrix A, i.e., find The matrix A equals the matrix L times the matrix U. For this decomposition, find the transformed set of equations Matrix L times vector y equals vector b. Solve the system of equations Matrix L times vector y equals vector b for the unknown vector The vector y.

Use MATLAB to compute the inverse of The matrix Uusing the inv() function.
Compute the solution to the original system of equations by transforming The vector y into The vector x, i.e., compute The vector x equals the inverse of matrix U times the vector y.

Check your answer for x one using Cramer’s Rule.

Use MATLAB to compute the required determinants using the det() function. The Project One Table Template, provided in the Supporting Materials section, shows the recommended throughput capacity of each link in the network. Put your solution for the system of equations in the third column so it can be easily compared to the maximum capacity in the second column. In the fourth column of the table, provide recommendations for how the network should be modified based on your network throughput analysis findings. The modification options can be No Change, Remove Link, or Upgrade Link. In the final column, explain how you arrived at your recommendation.

