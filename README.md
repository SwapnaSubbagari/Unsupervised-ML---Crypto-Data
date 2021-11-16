# Unsupervised-ML---Crypto-Data
Unsupervised Learning with Cryptocurrency Data
Purpose
This project aimed to (a) use various unsupervised learning strategies and (b) determine whether select cryptocurrency data can be groups in distinct clusters.

# Steps
1.	Preprocessing the data
2.	Dimension reduction via Principal Component Analysis (PCA)
3.	Use of the TNSE to further reduce data complexity
4.	Summarize with K-Means Cluster Analysis to determine relevant cluster

# Tools
•	Jupyter Lab

•	Opensource data from Crypto Compare

•	Packages: Pandas, Numbpy, matplotlib, sklearn

# Results
There were a total of 532 cryptocurrencies with complete data that were trading when the data was uploaded.

The PCA revealed 74 principal components (out of a potential 98), which explained 90% of the variance in the data. We then used TSNE to reduce the features in the data further. TSNE revealed that there were two features in the data based on its algorithm. A plot of the features is below.
![image](https://user-images.githubusercontent.com/85588653/141883630-c1939e5d-8eae-4da8-90a2-556835bbe29b.png)

Next, we used K-Means to determine whether we could reveal clusters in the data not otherwise obtained from the PCA output data. Based on the elbow plot, there were no distinguishable clusters. As you can see in the figure below, there is no distinguishable elbow.
![image](https://user-images.githubusercontent.com/85588653/141883689-f5288315-8ff6-44da-ab25-bdb7812ffab7.png)
