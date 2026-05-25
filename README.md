# Implementation-of-K-Means-Clustering-for-Customer-Segmentation

## AIM:
To write a program to implement the K Means Clustering for Customer Segmentation.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 1.Import Libraries and Load Dataset Import required Python libraries and read the customer dataset using pandas.

2.Select Required Features Choose the columns Annual Income and Spending Score for clustering.

3.Apply K-Means Clustering Create the K-Means model with 5 clusters and fit it to the selected data.

4.Predict Customer Clusters Assign each customer to a cluster using the trained K-Means model.

5.Visualize the Clusters Plot the customer groups and centroids using a scatter plot with labels and title.


## Program:
```
/*
Program to implement the K Means Clustering for Customer Segmentation.
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans

data = pd.read_csv("Mall_Customer.csv")

X = data.iloc[:, [3, 4]].values

kmeans = KMeans(n_clusters=5, random_state=0)

y_kmeans = kmeans.fit_predict(X)

plt.scatter(X[:, 0], X[:, 1], c=y_kmeans, s=50)

# Plot centroids
plt.scatter(kmeans.cluster_centers_[:, 0],
            kmeans.cluster_centers_[:, 1],
            s=200,
            marker='X')

# Labels
plt.xlabel("Annual Income")
plt.ylabel("Spending Score")
plt.title("Customer Segmentation using K-Means")

plt.show()
Developed by: R.Rachanaa
RegisterNumber: 212225040322 
*/
```

/*
Program to implement the K Means Clustering for Customer Segmentation.
Developed by: Harini V K
RegisterNumber:  212225220036
*/


## Output:
<img width="1002" height="707" alt="image" src="https://github.com/user-attachments/assets/8aa409bf-0f75-44a5-b1cb-537498d0db88" />



## Result:
Thus the program to implement the K Means Clustering for Customer Segmentation is written and verified using python programming.
