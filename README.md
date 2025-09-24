# Chat Log Analysis and Clustering

This project focuses on analyzing and clustering customer support tweets to uncover patterns in customer queries.

We utilize the **[Customer Support on Twitter dataset](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)** from Kaggle, which contains a large collection of tweets directed at various companies. The dataset is ideal for studying real-world customer service interactions.

For our analysis, we specifically focus on the **initial tweets** that customers send to initiate conversations, as these messages are most likely to contain the core problem statement.

---

## 📂 Project Workflow

1. **Dataset Preparation – First Query To AmazonHelp**  
   - Filters the raw Kaggle dataset to retain only the first customer queries directed at `@AmazonHelp`.  
   - The processed dataset is saved as **`first_queries_to_amazonhelp.csv`**.  

2. **Amazon Tweets Dataset Analysis**  
   - Explores and visualizes the processed dataset to gain insights into customer issues, trends, and tweet characteristics.  

3. **Amazon Tweets Clustering**  
   - Applies clustering techniques to group similar customer queries, helping identify recurring topics and patterns.
