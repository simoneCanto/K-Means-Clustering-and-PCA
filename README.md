# K-Means-Clustering-and-PCA

## K-means Clustering and Principal Component
## Analysis
## Machine Learning

Introduction

In this exercise, you will implement the K-means clustering algorithm and apply it to compress an image. In the second part, you will use principal component analysis to find a low-dimensional representation of face images.

Before starting on the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics. To get started with the exercise, you will need to download the starter code and unzip its contents to the directory where you wish to complete the exercise. If needed, use the cd command in Octave/MATLAB to change to this directory before starting this exercise.

You can also find instructions for installing Octave/MATLAB in the \Environment Setup Instructions" of the course website. Files included in this exercise:

1. ex7.m - Octave/MATLAB script for the first exercise on K-means
2. ex7 pca.m - Octave/MATLAB script for the second exercise on PCA
3. ex7data1.mat - Example Dataset for PCA
4. ex7data2.mat - Example Dataset for K-means
5. ex7faces.mat - Faces Dataset
6. bird small.png - Example Image
7. displayData.m - Displays 2D data stored in a matrix
8. drawLine.m - Draws a line over an exsiting figure
9. plotDataPoints.m - Initialization for K-means centroids
10. plotProgresskMeans.m - Plots each step of K-means as it proceeds
11. 1runkMeans.m - Runs the K-means algorithm
12. submit.m - Submission script that sends your solutions to our servers
13. pca.m - Perform principal component analysis
14. projectData.m - Projects a data set into a lower dimensional space
15. recoverData.m - Recovers the original data from the projection
16. findClosestCentroids.m - Find closest centroids (used in K-means)
17. computeCentroids.m - Compute centroid means (used in K-means)
18. kMeansInitCentroids.m - Initialization for K-means centroids
19. indicates files you will need to complete
    
Throughout the first part of the exercise, you will be using the script ex7.m, for the second part you will use ex7 pca.m. These scripts set up the dataset for the problems and make calls to functions that you will write. You are only required to modify functions in other files, by following the instructions in this assignment.
