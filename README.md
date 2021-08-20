# Identify-Customer-Segments

This project identifies what kind of people in Germany are likely to be a customer of a mail-order sales company.
Several data files have been used such as the the feature information of the general public, feature information of the customers and the feature explanation file. Unfortunately, these files cannot be shared with the public.
The procedure is as follows:
1. Load the general population data.
2. Preprocessing including handling NaN's, reencoding, one-hot encoding.
3. Feature transformation including scaling, dimensionality reduction through PCA.
4. Clustering with K-means algorithm.
5. Load the customer data. Repeat step 2. Use "Transform" to copy scaling, PCA and K-means model from the general population to the customers.
6. Predict the labels for the general population and the customers.
7. Identify the labels that are overrepresented and underrepresented among the customers.
8. By using inverse transform, identify what kind of a person would be more or less likely to be a customer of a mail-order sales company.

Results show that the customers tend to be richer and older.
