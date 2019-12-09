
# PCA - Recap


## Key Takeways 

The key takeaways from this section include: 

* PCA is an _unsupervised learning technique_ which does not require labeled data 
* It is also a dimensionality reduction technique which can be used to compress data, and experiment with its effect on machine learning algorithms as a preprocessing step 
* There are four steps to calculating PCA:
    * Center each feature by subtracting the feature mean
    * Calculate the covariance matrix for your normalized dataset
    * Calculate the eigenvectors/eigenvalues for the covariance matrix
        * Reorder your eigenvectors based on their accompanying eigenvalues (descending order to the eigenvalues)
    * Take the dot product of the transpose of the eigenvectors with the transpose of the normalized data
* You can also easily implement PCA using scikit-learn 
