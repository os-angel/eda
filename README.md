# Exploratory Data Analysis and K-means Clustering for Fraud Detection

## **Description**


The dataset contains credit card transactions made in September 2013 by some cardholders. In total, the dataset contains 293 fraudulent transactions out of 284,807.
The data contains numerical values due to a transformation from a principal component analysis (PCA). Further personal information about the credit card owners is not available, thus ensuring data confidentiality.
We are going to apply an unsupervised ML algorithm (**K-Means**) to be able to group and predict fraudulent transactions based on input features.


## **Data Download**
The data is available on Kaggle for replication.
[CreditCardFraudDetection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

<img width="779" alt="Captura de pantalla 2024-12-10 a la(s) 11 28 48 a  m" src="https://github.com/user-attachments/assets/85ac6e00-e638-46cf-bd07-e3703a2e2f07">


## **Summary**
This notebook applies the unsupervised machine learning algorithm K-Means to group and predict fraudulent transactions based on input features from a credit card transaction dataset. The notebook performs exploratory data analysis, prepares the data, trains the K-Means model, and evaluates the results using the purity score, silhouette score, and Calinski-Harabasz score.

## **Introduction**
The dataset contains credit card transactions made in September 2013 by some cardholders. In total, the dataset contains 293 fraudulent transactions out of 284,807. The data contains numerical values due to a transformation from a principal component analysis (PCA). Further personal information about the credit card owners is not available, thus ensuring data confidentiality. The goal is to apply an unsupervised ML algorithm (K-Means) to be able to group and predict fraudulent transactions based on input features.

## **Conclusion**
The clustering results indicate a high purity score (0.999), suggesting that the clusters are relatively homogeneous and contain mostly data points from the same class. However, the relatively low Silhouette score (0.179) indicates that the clusters might be overlapping or not well-separated. Despite this, the Calinski-Harabasz score (38466) is high, suggesting a good overall clustering structure with dense and well-separated clusters. Overall, the K-Means model shows promising performance in identifying fraudulent transactions, but further improvements might be needed to enhance cluster separation.



Feel free to contact me: anaj9703@colorado.edu
