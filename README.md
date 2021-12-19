# Cryptocurrencies Analysis
The purpose of the Cryptocurrentcies Analysis was to create a report indicating what cryptocurrencies are on the trading market and how they could be grouped to create a classification system that would be used to inform a new cryptocurrency investment portfolio for customers. First, data was preprocessed and the features standardized using the StandardScaler function. Then, a Principal Components Analysis (PCA) was performed on the data in order to reduce data dimensions down to three components. Next, an elbow curve was generated in order to find the best value for k, which was determined to be four. The KMeans algorithm was used to make predictions of the K clusters for the cryptocurrencies data. Finally, the data was visualized using a 3D scatterplot and an hvplot scatterplot.

## Resources
- Data Sources:  crypto_data.csv
- Software: Jupyter Notebook, Python, Pandas, scikit-learn, plotly.express

## Visualizations
The Jupyter Notebook, crypto_clustering.ipynb, uploaded to this repository contains all of the code used to perform this analysis. The visualizations in the notebook are presented below as the notebook did not translate these visualizations to GitHub. 

### (1) Elbow Curve

![image](https://user-images.githubusercontent.com/85533099/146660465-9b17f1fe-5f36-4963-9d6a-85fc29e60bfc.png)

![image](https://user-images.githubusercontent.com/85533099/146660470-fb1a9ab3-e48c-41b4-96f6-6cb288aa0187.png)

### (2) 3-D Scatterplot

![image](https://user-images.githubusercontent.com/85533099/146660723-4756e9c4-1be6-4f2e-891b-5b434c7157e1.png)

![image](https://user-images.githubusercontent.com/85533099/146660725-744a4265-0392-4cda-83fd-ecb4bea1e32a.png)

### (3) Table Containing Tradable Cryptocurrencies

![image](https://user-images.githubusercontent.com/85533099/146660738-a455b395-1961-42da-83c6-34b7f408ab44.png)

### (4) Hvplot Scatterplot

![image](https://user-images.githubusercontent.com/85533099/146660750-f51936f6-2821-4da5-8d4d-1b0d77842022.png)


