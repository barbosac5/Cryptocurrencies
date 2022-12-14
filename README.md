# Cryptocurrencies
## Purpose 
The purpose of this challnege is to to use machine learning models in order to group cryptocurrencies. To do this I decided on a clustering algorithm with the cryptocurrency data csv provided to me.

## Results 
### Deliverable 1: Preprocessing the Data for PCA
Using my knowledge on Pandas, I preprocessed the dataset in order to perform PCA in the next Deliverable 

#### Deliverable 1 Preprocessing
![clean_crypto_df](./Cryptocurrencies/clean_crypto_df.png)

### Deliverable 2: Reducing Data Dimensions Using PCA
Here I applied the Pricipal Component Analysis algorithm to reduce the dimensions of the X DataFrame to three pricipal components and place these dimesions in a new DataFrame 

#### Reducing Data Dimensions 
![clean_crypto_pca](./Cryptocurrencies/clean_crypto_pca.png)

### Deliverable 3: Clustering CryptoCurrencies Using K-Means
Using my knowledge of the K-Means algorithm, I created an elbow curve using hvPlot to find the best value for K from the pcs DataFrame created in Delvierable 2. The I ran the K-Means algorithm to predict the K clusters for the crypto data.

#### Elbow Curve
![Elbow_Curve](./Cryptocurrencies/Elbow_Curve.png)

#### Clustering Crypto using K-Means
![Deliverable_3_clustered_df](./Cryptocurrencies/Deliverable_3_clustered_df.png)

### Deliverable 4: Visualzing Cryptocurrencies Results 
I created scatter plots with plotly Express and hvplot. I visualized the distince groups that corresponded to the three principal components made in Deliverable 2. Finally, I created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

#### Visualzing Results (3D Plot)
![3D_plot](./Cryptocurrencies/3D_Plot.png)

#### DataFrames for Deliverable 4
![hvplot_table](./Cryptocurrencies/hvplot_table.png)

![clustered_df](./Cryptocurrencies/clustered_df.png)

#### Scatter Plot
![crypto_scatter](./Cryptocurrencies/crypto_scatter.png)

## Resources
- Pandas
- Jupyter Notebook 
- hvplot
- Plotly Express
- PCA
- StandardScaler
- MinMaxScaler
- KMeans

