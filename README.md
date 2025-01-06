# Mall Customer Segmentation

## Overview
This project demonstrates the steps for clustering mall customers based on their annual income and spending score. The goal is to identify distinct customer segments for better targeting and personalized marketing strategies.

## Dataset
The dataset used in this project is `Mall_Customers.csv`, which contains the following features:
- **CustomerID**: Unique ID assigned to each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: Spending score assigned to the customer based on their behavior and spending nature.

## Steps
1. **Loading the Data**: Reading the dataset and displaying basic statistics.
2. **Data Visualization**: Visualizing the distributions of age, annual income, and spending score.
3. **Gender Composition Analysis**: Examining the gender distribution in the dataset.
4. **Data Preprocessing**: Converting the 'Gender' column to numerical values.
5. **Correlation Analysis**: Creating a heatmap to visualize the correlation between different features.
6. **Feature Standardization**: Standardizing the annual income and spending score features.
7. **Elbow Method**: Using the Elbow Method to determine the optimal number of clusters.
8. **KMeans Clustering**: Applying KMeans clustering with the optimal number of clusters.
9. **Cluster Visualization**: Visualizing the customer segments using a scatter plot.
10. **Cluster Analysis**: Analyzing the characteristics of each cluster.
11. **Insights and Recommendations**: Providing insights and recommendations based on the cluster analysis.

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage
1. **Install the required libraries**:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```

2. **Run the Jupyter Notebook**:
    - Open the Jupyter Notebook and run the cells sequentially.
    - Follow the markdown descriptions and code snippets to understand the steps involved.

## Insights and Conclusions
Based on the cluster analysis, the following insights and recommendations are drawn:

1. **Cluster 0**: Customers with moderate income and spending scores.
2. **Cluster 1**: High-income customers with low spending scores. Potential to convert them into higher-spending customers with targeted marketing.
3. **Cluster 2**: Low-income customers with low spending scores. They are likely price-sensitive.
4. **Cluster 3**: Low-income customers with high spending scores. These could be loyal customers worth retaining.
5. **Cluster 4**: High-income customers with high spending scores. These are premium customers and can be targeted for exclusive services or products.

### Recommendations
- Focus on Cluster 4 for premium services.
- Engage Cluster 1 with personalized offers to increase their spending.
- Retain Cluster 3 by offering loyalty programs.

## Conclusion
This project provides a comprehensive approach to segmenting customers in a mall based on their annual income and spending score. The insights gained from clustering can help in devising targeted marketing strategies and improving customer satisfaction.

## Acknowledgements
- The dataset used in this project is publicly available.
- Special thanks to the contributors of the libraries used in this project.
