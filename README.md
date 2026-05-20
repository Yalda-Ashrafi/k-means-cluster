# k-means-cluster
I applied the K-Means Clustering algorithm to the Mall_customers.csv dataset. The goal is to uncover hidden patterns in customer spending habits to effectively segment the mall's client base for targeted marketing strategies.

🧬 The Dataset
The dataset contains information about mall customers used to group them into distinct segments based on behavior and demographics.

Key Features:

CustomerID: Unique ID assigned to the customer.  

Gender: Gender of the customer.  

Age: Age of the customer.  

Annual Income (k$): Annual income of the customer.  

Spending Score (1-100): Score assigned by the mall based on behavior and spending nature.  

Note: For this implementation, the model specifically focuses on Annual Income and Spending Score to identify target customer groups.

⚙️ Methodology
Optimal Clusters: By calculating the Within-Cluster Sum of Squares (WCSS) and using the Elbow Method, I determined the optimal number of clusters.

Clustering: I used the Scikit-Learn KMeans library to partition the data into distinct groups.

Visualization: The results help identify high-value customers (high income, high spend) versus other demographic groups.

🔗 Data Source
You can find the dataset used in this project here:

Download Mall_customers.csv  https://drive.google.com/file/d/1m7TAs1wMapSjE6PzIzc0Qe-TjZj4y1pz/view?usp=sharing
