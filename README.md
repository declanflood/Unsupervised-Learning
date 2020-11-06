# Identify Customer Segments - Unsupervised Learning Project

After substantial data preparation, this project used PCA and k-means clustering to solve a customer segmentation problem.

Two sets of demographics data were used: for 900k individuals from the general population of Germany, and 200k existing customers of a mail-order company. Data preparation included applying an approach to deal with missing data before re-encoding non-numerical and mixed-type features. 63 features were selected for further analysis. These were scaled and a PCA algorithm was used to create 25 principal components. K-means clustering was applied to the transformed data and 12 clusters were identified. These steps were applied to the general population data first, and then to the existing customers data. The distribuition of data accross the 12 clusters differed between the two data sets. This provided insight on potentially useful target customer segments for the company.
