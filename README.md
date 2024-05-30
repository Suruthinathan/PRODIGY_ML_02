# Retail Store Customer Segmentation using K-Means Clustering
This project aims to segment customers of a retail store based on their purchase history using the K-means clustering algorithm. By analyzing customer purchase data, we can identify distinct groups of customers, which can help in targeted marketing and personalized customer service.The dataset used is from [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).

# Project Structure
1. data: Directory containing the dataset.
   - Mall_Customers.csv: The dataset used for clustering.
2. notebooks: Directory containing Jupyter Notebooks
   - customer_segmentation.ipynb: The main notebook with the implementation of the K-means clustering algorithm.
3. README.md: Project documentation.

# Dataset
The dataset used in this project is Mall_Customers.csv, which contains the following columns:

- CustomerID: Unique identifier for each customer.
+ Gender: Gender of the customer.
* Age: Age of the customer.
- Annual Income (k$): Annual income of the customer in thousands of dollars.
+ Spending Score (1-100): Score assigned by the store based on customer behavior and spending nature.

# Prerequisites
Ensure you have the following libraries installed:

- pandas
+ numpy
* matplotlib
- seaborn
+ scikit-learn
  
You can install these libraries using pip:
```
pip install pandas scikit-learn matplotlib
```

# Results
The clusters obtained from the K-means algorithm can be used to understand different segments of customers based on their annual income and spending score. These insights can be leveraged for targeted marketing strategies.

# Acknowledgements
The project uses the dataset from the [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). competition on Kaggle.
