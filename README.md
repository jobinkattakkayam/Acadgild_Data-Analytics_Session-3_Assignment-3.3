# Acadgild_Data-Analytics_Session-3-Assignment-3.3

# Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum over rows and columns.

mymat <- matrix(rep(1:5), nrow=5, ncol=4) 

mymat

colSums(mymat) 

rowSums(mymat)
