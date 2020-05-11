# PCA-R
This is an implementation of Principal Component Analysis in R on the Iris dataset.  
There are three distance metrics used to calculate the inter and intra species distance and find out how well they are able to distinguish between the species. They are as follows:  
- Euclidean Distance
- Cosine Distance
- L-infinty Distance

The function ```principal_component_analysis``` calculates the principal components of the dataset.  

```principal_component_calculation``` calculates the PC given a data object and component weights.  

The ```pc1_distance``` function takes in two data objects (vectors) and a set of PC weights, and returns the distance between those two vectors in the dimension of the first PC, i.e. the absolute difference between their PC values.  
