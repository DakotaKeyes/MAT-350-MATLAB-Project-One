# MAT-350-MATLAB-Project
Image Compression using Single Value Decomposition  

You are employed as a computer programmer for a popular social media site that stores a large amount of user media files. You believe you have found a way to reduce costs by compressing image files using singular-value decomposition (SVD). The compressed files would require less storage space, which would result in savings for the company. You think it will work, but you want to test your theory and record the steps you take to use as a reference when sharing your idea with management.

Directions
In order to guarantee that management fully understands the process, you have mapped out the following steps to ensure you have captured the process and have data to support your findings and to share with management. Your plan is to demonstrate computations on a simple 3 x 3 matrix where the computations are easier to follow. Then you will perform similar computations on a large image to compress the image data without significantly degrading image quality.

To develop your idea proposal, work the problems described below. As you complete each part, make sure to show your work and carefully describe how you arrive at your final answer. Any MATLAB code or MATLAB terminal outputs you generate should be included in your idea proposal to support your answers and work.

Consider the matrix: three-by-three:


Use the svd() function in MATLAB to compute The matrix A one, the rank-1 approximation of The matrix A. Clearly state what The matrix A one is, rounded to 4 decimal places. Also, compute the root mean square error (RMSE) between The matrix A and The matrix A one.

Use the svd() function in MATLAB to compute The matrix A two, the rank-2 approximation of The matrix A. Clearly state what The matrix A two is, rounded to 4 decimal places. Also, compute the root mean square error (RMSE) between The matrix A and The matrix A two. Which approximation is better, The matrix A one or The matrix A two? Explain.

For the three-by-three matrix The matrix A, the singular value decomposition is The matrix A equals the matrix U times the matrix S times the transpose of matrix V where The matrix U equals a matrix with three columns. The three columns are the vectors u one, u two, and u three.. Use MATLAB to compute the dot product The dot product scalar value d one is equal to the dot product between vectors u one and u two.. Also, use MATLAB to compute the cross product The vector cross product c is equal to the cross product between vectors u one and u two. and dot product The dot product scalar value d two is equal to the dot product between vectors c and u three. . Clearly state the values for each of these computations. Do these values make sense? Explain.

Using the matrix The matrix U equals a matrix with three columns. The three columns are the vectors u one, u two, and u three., determine whether or not the columns of The matrix U span The vector space R three. Explain your approach.

Use the MATLAB imshow() function to load and display the image The matrix A stored in the provided MATLAB image.mat file (available in the Supporting Materials area). For the loaded image, derive the value of The discrete value k that will result in a compression ratio of C R the compression ratio is approximately equal to two.. For this value of The discrete value k, construct the rank-The discrete value k approximation of the image.

Display the image and compute the root mean square error (RMSE) between the approximation and the original image. Make sure to include a copy of the approximate image in your report.

Repeat steps 5 and 6 for C R the compression ratio is approximately equal to ten., C R the compression ratio is approximately equal to twenty-five., and C R the compression ratio is approximately equal to seventy-five.. Explain what trends you observe in the image approximation as C R the compression ratio increases and provide your recommendation for the best C R the compression ratio based on your observations. Make sure to include a copy of the approximate images in your report.

What to Submit
To complete this project, you must submit the following:

Use the provided Project Two Template as the starting point for your project solution. Complete each portion of the template, run the project, and then export your work as a single PDF file. Upload this PDF document that shows your answers and supporting work for the problems described above. Make sure to include explanations of your work, as well as all MATLAB code and outputs of the computations.

