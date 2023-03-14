Customer Segmentation

Businesses often prefer to segment their customers so that they may develop unique marketing strategies for each group of customers.
This project aims to cluster the types of customers.

Dataset

I used the customer segmentation dataset on Kaggle, which contains the basic information about the customers - the customers' age, gender, annual income, 
and spending score. The data set has 200 rows and 5 columns.

Data Pre-processing

I performed a pre-processing step to prepare the data for clustering. This included scaling numerical data and encode the categorical data.

Model Selection and Training

For clustering I used the following algorithms K-Means, Hierarchical clustering - AHC and GaussianMixture.
For dimensionality redaction I used PSA and t-NSE algorithms.


Results

The best model was Gaussian mixed model after t-SNE 2 features dimension reduction who achieved a silhouette score of 0.60.
