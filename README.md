# Clustering-and-PCA
HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.

After the recent funding programmes, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid. 

And this is where you come in as a data analyst. Your job is to categorise the countries using some socio-economic and health factors that determine the overall development of the country. Then you need to suggest the countries which the CEO needs to focus on the most.  The datasets containing those socio-economic factors and the corresponding data dictionary are provided below.


# Read Data
Import important libraries
Read country data into dataframe
Shape of country_data dataframe
Quick review of country_data dataframe
Converting % GDP columns

# Analyze Data
Check for missing values

# Data Preparation for Modeling
Use standard scaler to scale the numerical data

# Find Principal Components using PCA
Initiate PCA object, fit object and review components
Scree plot to check variance explained by PCs
Building PCA for country data using optimal PCs(5)
Heatmap to verify multicollinearity
Outlier Analysis on PCs
Remove outliers from PC dataframe
Check hopkins score

# Clustering using KMeans
Optimal cluster using elbow curve
Optimal cluster using silhouette score
Building model using optimal cluster(k)
Visualizing clusters formed by kmeans

# Clustering using Hierarchical clustering
Using single linkage (Minimum distance)
Optimal cluster using silhouette score
Visualizing clusters formed by Hierarchical

# Conclusion
List countries in cluster with lowest income, lowest gdpp and highest child mort
