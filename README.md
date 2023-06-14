### Best-City_toMove-with-PCA

Read the data and construct a table with 9 columns containing the numerical ratings. 
Replace each value in the matrix by its base-10 logarithm. 
This pre-processing is done for convenience since the numerical range of the ratings is large.
We create a data matrix X whose rows are 9-dimensional vectors representing the different cities.

 Perform PCA on the data. 
 We center the data points first by computing the mean data vector µ and subtracting it from every point. 
 With the centered data matrix, do an SVD and compute the principal components.

 Calculate correlation for first two principal components v1 and v2 and Provide a qualitative interpretation
 of the components.
 Find factors they appear to correlate with.

  Project the data points onto the first two principal components.
  Plot the scores as a 2D scatter plot. 
  Detect cities correspond to outliers in this scatter plot

![SP](https://github.com/im-Shree/Best-City_toMove-with-PCA/assets/90651908/197c03b5-90a8-4d53-a632-8e8ec53699c1)

  

  We can repeat it but with a slightly different data matrix – instead of computing the base-10
  logarithm, use the normalized z-score of each data point. How do your answers change?
