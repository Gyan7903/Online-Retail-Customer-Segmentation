# Online-Retail-Customer-Segmentation
After basic exploration and cleaning the data we found relationships between features in EDA and then jumped into the analysis part. RFM analysis helped us to identify the Platinum and Gold Customers who brings more profit for the Online retail stores as well helped to focus on Silver and Broze type of customer by organising some attractive offers for them.
We implemented various unsupervised machine learning algorithm such as KMeans Clustering, DBSCAN Algorithm , Hierarchical Clustering(Agglomerative Clustering). Here to find the Optimal number of clusters we used Elbow method as well as used a Elbow Visulizers by Yellow bricks from Scikit Learn library. Also we used Silhouette Score and Silhouette Plot to visualize the clusters with different number of clusters. For Agglomerative Clustering we used Dendogram to find the optimal number of clusters.
# Problem Description
In this project, our task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
# Data Description
Attribute Information:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
# Challenges
* Data cleaning
* RFM analysis
* Deciding optimal number of clusters
