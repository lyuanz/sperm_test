Don't loop over x and y. 
Try using only numpy to calculate the spread coefficient.
Don't use += or its equivalents. Doesn't work with parallel computing. 
Store values in an empty array instead, then exit parallel computing and use np.sum