# Cryptocurrencies
Challenge 18

#Porpouse
The purpose of this challenge is to help a prominent investment bank who is interested in offering a new cryptocurrency investment portfolio for its customers.

Based on the experience acquired in the module, it will be used unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principal components using PCA.

# Preprocessing the Data for PCA

##Deliverable 1

### Load the crypto_data.csv dataset

![image](https://user-images.githubusercontent.com/96089967/168169639-b643877d-e7a5-4b21-afac-10d0b11e9d32.png)


### Keep all the cryptocurrencies that are being traded.

![image](https://user-images.githubusercontent.com/96089967/168169784-049a51cd-6b6f-41c9-821f-044e757eef61.png)


### Keep all the cryptocurrencies that have a working algorithm.

![image](https://user-images.githubusercontent.com/96089967/168169903-71ae1963-ed25-4540-b817-57c400f6e58e.png)


### Remove the "IsTrading" column. 

![image](https://user-images.githubusercontent.com/96089967/168170377-86e2c976-38fb-47f3-a00e-26bbfda586e9.png)


### Remove rows that have at least 1 null value.

![image](https://user-images.githubusercontent.com/96089967/168170499-c3335712-711f-4b1c-9e5d-f31c49673132.png)

### Keep the rows where coins are mined.

![image](https://user-images.githubusercontent.com/96089967/168170638-fc620818-483d-4eab-ad1c-ff6f91d0d3d6.png)


## Create a new DataFrame that holds only the cryptocurrencies names.

![image](https://user-images.githubusercontent.com/96089967/168170887-3d8d2875-52ec-4b6a-95fc-ad660435dcbd.png)

### Drop the 'CoinName' column since it's not going to be used on the clustering algorithm.

![image](https://user-images.githubusercontent.com/96089967/168171032-c0180630-fac1-4ec8-b96f-a428f2b7cca0.png)

### Use get_dummies() to create variables for text features.

![image](https://user-images.githubusercontent.com/96089967/168172196-bf019fc9-f5da-4da5-a8c7-8852157eeb81.png)

### Standardize the data with StandardScaler().

![image](https://user-images.githubusercontent.com/96089967/168172312-ab86d1ec-43df-4873-ab3f-6591351a83dc.png)


## Deliverable 2

### Create a DataFrame with the three principal components.
![image](https://user-images.githubusercontent.com/96089967/168172826-1fcee457-4397-4f23-9816-5bf8a35870f5.png)


## Deliverable 3:Clustering Crytocurrencies Using K-Means

![image](https://user-images.githubusercontent.com/96089967/168173174-cc44e26e-9287-4ceb-a232-09117f2bdbe6.png)


## Create a new DataFrame including predicted clusters and cryptocurrencies features.

![image](https://user-images.githubusercontent.com/96089967/168173338-7a104ac6-20c7-4eed-aa3c-19e6659bbd34.png)

# Deliverable 4: Visualizing Cryptocurrencies Results

### Creating a 3D-Scatter with the PCA data and the clusters

![image](https://user-images.githubusercontent.com/96089967/168174248-3178fa24-f27c-446b-93be-c5de34e001dd.png)


### Create a table with tradable cryptocurrencies.

![image](https://user-images.githubusercontent.com/96089967/168174377-dbf63c8b-2ce1-47e1-8050-ff10a4e2ce5f.png)

### Create a hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply".

![image](https://user-images.githubusercontent.com/96089967/168174471-fc85dcb6-0fed-4dbb-a4bb-3cbf6a19caf0.png)





