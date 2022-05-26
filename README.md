# Cryptocurrencies - Unsupervised Machine Learnin

## Project Overview 
For this project we are going to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.  
Achieving this, we can offer a new cryptocurrency investment portfolio for the customers at Accountability Accounting.

Here´s a description of the following steps to take:  
- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCA
- Clustering Cryptocurrencies Using K-means
- Visualizing Cryptocurrencies Results


## Resources
Data Source: crypto_data.csv, CryptoCompare
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results  
Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.  

### Clustering Cryptocurrencies using K-Means - Elbow Curve  
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.  
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.  
![Elbow curve](https://github.com/ManuelRuizF/Cryptocurrencies-Unsupervised-Machine-Learning/blob/main/elbow%20curvee.PNG)  
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.
- The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

## Summary 
We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.
