# Sf_data_science_project-6

# Project 6. Segmentation of gift shop cleints


### Project description    
Clusterisation of a gift shop clients.
The data set that contains all transactions that occurred between 01/12/2010 and 09/12/2011 for a UK-based online retailer. The company primarily sells unique gifts for all occasions. Many of the company's customers are wholesalers.


### Case to solve    
Perform clients segmentation, interpret the reulsts and determine a strategy for interacting with them.

Create a clusterisation model based on their purchasing power, order frequency and the time since their last purchase.
Determine the profile of each cluster.



### Short summary of data
The dataset stores information on a range of features, including:
* invoice number ("C" is for transaction cancelling),
* stock code (unique for each good),
* good description, 
* good quantity,
* invoice date,
* price for one unit (in pounds), 
* customer ID (unique, five digits),
* country.



### Project stages  
Study the structure of the data.
Pre-process and clean the dataset.
Perform EDA.
Choose the best clusterisation model and perform segmentation.




### Results:  

The code for data processing is here (https://github.com/dv-nova/SF_DS_p6/)

 Visualisations after EDA:
 
 https://github.com/dv-nova/SF_DS_p6/blob/main/Seasonal_revenue.png
 
 https://github.com/dv-nova/SF_DS_p6/blob/main/Seasonal_revenue_by_countries.png
 
 https://github.com/dv-nova/SF_DS_p6/blob/main/Total_revenue_by_countries.png
 
 https://github.com/dv-nova/SF_DS_p6/blob/main/Num_of_transactions_by_countries.png

### Conclusions:  
All the tasks are solved.

The dataset was investigated and prepared for further analysis.
EDA was performed. The top 6 highest year revenue is obtained from clients living in UK, Netherlands, Germany, France, EIRE, and Australia. Sellings are subject to seasonal factor, with the greatest revenue earned in Autumn. Since UK brings the highest revenue, the regional features could be studied to maintain the revenue and attract clients from other regions. Since Black Friday is held in Autumn in UK, the skewness to this factor can be studied in depth for more effectiveness of selligns.
The peak of transactions occurs at 12:00, which could be the prime time for attracting the clients with advertisments.

The data was divided into three main segments. First, the cluster of perspective clients and newbies. These clients can potentially bring more revenue in future. Second, the segment of clients who brought high revenue in past, but are not active in the end of the analysed period. Threfore, these clients are "sleeping" or at the edge of being lost and require further actions to be turned into loyal. An advertising campaign could bring them back. Third, the last category includes clients with low frequency and recency. These clients acquired goods only at the start of the period, but the number of transcations is also low. Threfore, these clients are potentially lost due to their low activity for a long time. Possibly, a research on shortcomings of the business, conducting a survey of client preferenes could close the gap. 

