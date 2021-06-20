# Cryptocurrencies
MODULE 18 - Unsupervised Machine Learning and Cryptocurrencies

## OVERVIEW
#### Purpose: Using unsupervised machine learning algorithms on data received from CryptoCompare.com, this analysis addresses what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for new investment purposes.  The raw data was imported, then preprocessed (cleaned and transformed) for analysis (Deliverable 1). It was then reduced using principal component analysis (PCA) to three (3) principal components (Deliverable 2). Using the k-means algorithm, the data was then clustered (Deliverable 3).  Finally, the results were [visualized](Images/4_1.png) using a 3-D scatter plot by principal components, a table of (532) tradable cryptocurrencies and a [2-d scatter plot](Images/4_2.png) showing clusters ("Class") by Total Coin Supply and Total Coins Mined (Deliverable 4).

## RESOURCES
  - DATA Source: [crypto_data.csv](Resources/crypto_data.csv)
  - Software:  Python, Anaconda, Jupyter Notebooks, Pandas, hvplot, plotly.express, sklearn.preprocessing (StandardScaler and MinMaxScaler), sklearn.decomposition (PCA), sklearn.cluster (KMeans)


## SUMMARY

  - Deliverable 1: Preprocessing the Data for PCA ([Image 1.1](Images/1_1.png)), ([Image 1.2](Images/1_2.png)), ([Image 1.3](Images/1_3.png))
  - Deliverable 2: Reducing Data Dimensions Using PCA ([Image 2](Images/2_1.png))
  - Deliverable 3: Clustering Cryptocurrencies Using K-means ([Image 3.1](Images/3_1.png)), ([Image 3.2](Images/3_2.png))
  - Deliverable 4: Visualizing Cryptocurrencies Results ([Image 4.1](Images/4_1.png)), ([Image 4.2](Images/4_2.png))
