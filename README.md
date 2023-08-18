# Customer Segmentation

## Data
For the purpose of data collection, the Online Retail dataset available from UCI Machine Learning repository was utilized. This dataset comprises transactional records spanning from December 1st, 2010 to December 9th, 2011, capturing the transactions of a Europe-based online retail platform. Each row within the dataset represents a distinct transaction event. The dataset encompasses essential transaction details such as product names, quantities, prices, and distinctive identification columns. For analytical purposes, a subset of 10000 rows was thoughtfully sampled, thereby being regarded as a representative subset of the entirety of customer transactions.</br></br>

RFM
RFM stands for Recency, Frequency, and Monetary Value, and it is a widely used technique in marketing and customer analytics. RFM analysis is a method that categorizes customers based on their past behavior, focusing on three main aspects:

1. Recency (R): This refers to how recently a customer has made a purchase. Customers who have made a purchase more recently are considered more engaged and active.</br>

2. Frequency (F): Frequency indicates how often a customer makes purchases. Customers who make purchases frequently are typically more loyal and valuable to a business.</br>

3. Monetary Value (M): Monetary value represents the amount of money a customer has spent on purchases. High monetary value customers are often considered key contributors to a business's revenue.</br>

By evaluating these three aspects—Recency, Frequency, and Monetary Value—RFM analysis helps classify customers into different segments based on their behavior. This approach allows businesses to tailor their marketing strategies and engagement efforts to each segment's specific characteristics and needs.</br></br>
 
## Conclusion
Customer segmentation, a crucial endeavor, identifies distinct customer traits. K-Means clustering segments loyal, new, and churned customers. Cluster 2 comprises frequent, high-spending recent buyers—loyal customers. Cluster 0 includes less frequent, lower-spending recent buyers—new customers. Cluster 1 consists of infrequent, low-spending old-time buyers—churned customers.</br>

Suggestions:</br>

1. Elevate Cluster 0 by offering enticing deals to transform them into loyal customers and amplify profits.</br>
2. Focus less on Cluster 1 as it primarily constitutes churned-out customers with limited potential for enhancement.</br>
3. Prioritize Cluster 2—our loyal, vital segment—ensuring its growth and retention for shop success.</br>
