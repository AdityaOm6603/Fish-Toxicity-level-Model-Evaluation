### Project Title
#### Toxicity Data Analysis and Modeling

### Project Overview
This project aims to analyze a dataset to understand its characteristics and derive meaningful insights through data preprocessing, modeling, evaluation, and clustering. The dataset includes various features such as CIC0, SM1_Dz(Z), GATS1i, NdsCH, NdssC, MLOGP, and the response variable LC50 [-LOG(mol/L)].

### Table of Contents
->Project Overview
->Data Preprocessing
->Modeling
->Regression Models
->Multiple Linear Regression
->Ridge Regression
->Lasso Regression
->Classification Models
->Naive Bayes (Boosting)
->Voting Classification
->Clustering Models
->K-means Clustering
->DBSCAN
->Evaluation
->Conclusion

### Data Preprocessing
##### ->Handling Missing Values:
Imputation of missing values to prevent data loss and ensure a comprehensive dataset.
##### -Standardization and Normalization:
Standardizing the dataset to ensure that each feature contributes equally to the analysis.
##### -Feature Engineering:
Creating new features or modifying existing ones to improve model performance.
##### -Data Splitting:
Splitting the dataset into training and testing sets for model evaluation.

### Modeling
#### Regression Models(Best Models based on performane)
##### ->Multiple Linear Regression
Description:
Models the relationship between a dependent variable and multiple independent variables by fitting a linear equation.
Performance:
Reasonable performance with moderate MAE and MSE values and a good R2 score.
##### ->Ridge Regression
Description:
Includes a regularization term (L2 penalty) to prevent overfitting by shrinking the coefficients of less important features.
Performance:
Better generalization on the test set with slightly improved R2 scores and lower MSE values.
#### Classification Models(Best Models based on performance)
##### ->Naive Bayes (Boosting)
Description:
A probabilistic classifier based on Bayes' theorem, with boosting to combine multiple weak learners into a strong learner.
Performance:
High precision and recall, with a strong balance between the two metrics.
##### ->Voting Classification
Description:
Combines multiple models to improve performance by taking a majority vote for classification tasks.
Performance:
Highest F1-Score of 0.7824, showing strong predictive capability.
#### Clustering Models
##### ->K-means Clustering
Description:
Partitions data into K clusters by minimizing the variance within each cluster.
Performance:
Effectively identified distinct clusters, with Cluster 1 containing the majority of highly toxic data points.
##### ->DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
Description:
Groups closely packed points and marks points in low-density regions as outliers.
Performance:
Effective for identifying clusters of varying shapes and handling noise.

### Evaluation
Models were evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), R2 score, precision, recall, F1-score, Within-cluster Sum of Squares (WCSS), and Silhouette Score.

### Conclusion
The project provided valuable learning experiences, applying both new and revised concepts in data preprocessing, modeling, evaluation, and clustering. The analysis revealed significant patterns in the toxicity data, highlighting the distribution of highly, less, and medium toxic data points across different clusters.
