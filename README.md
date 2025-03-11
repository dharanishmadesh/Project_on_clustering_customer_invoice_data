

# 🛍️ Customer Segmentation Analysis with Clustering

This project performs customer segmentation using two clustering techniques: **K-Means** and **DBSCAN**. The goal is to segment customers based on their purchase behavior, such as their total bill size and purchase frequency.

## 📊 Overview

We use the **Online Retail dataset** to perform the following:

- **K-Means Clustering**: Customers are clustered based on their total spend using the `StandardScaler` and `KMeans` algorithm.
- **DBSCAN Clustering**: Another clustering method that works well with noise and varying density clusters.

Key features of customer behavior analyzed include:
- **Total Spend**: The sum of all purchases.
- **Purchase Interval**: The time span between the first and last purchases.

## 🔧 Requirements

To run the analysis, you'll need the following Python libraries:

- pandas
- numpy
- matplotlib
- scikit-learn

You can install them using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## 📥 Dataset

The dataset used is the **Online Retail dataset**, which can be accessed directly from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx).

## 🚀 How to Run

1. **Clone this repository**:

   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation
   ```

2. **Run the script**:

   You can run the `customer_segmentation.py` script to execute the clustering analysis:

   ```bash
   python customer_segmentation.py
   ```

3. The script will:
   - Read the data from the provided URL.
   - Perform data preprocessing (including calculating the total bill and purchase intervals).
   - Apply clustering techniques.
   - Visualize the results.
   - Print detailed cluster summaries.

## 💡 Features

- **K-Means Clustering**: This method segments customers into predefined clusters based on their total spending behavior.
- **DBSCAN Clustering**: A density-based clustering algorithm that can identify outliers (or noise) and forms clusters based on a region of high point density.

## 🔍 Results

The clustering results are displayed using a scatter plot and summarized by cluster, including:
- The number of customers in each cluster.
- The average total spend and purchase interval in each cluster.

You can analyze the output of the clustering in terms of customer behavior patterns.

## 📝 Example Output

**K-Means Summary**:

```
📊 Cluster 0 Summary:
📌 Number of Customers: 4337
💰 Average Spend: $1381.65

📊 Cluster 1 Summary:
📌 Number of Customers: 16
💰 Average Spend: $30720.77

📊 Cluster 2 Summary:
📌 Number of Customers: 7
💰 Average Spend: $52637.10
```

**DBSCAN Clustering Results**:

- Number of noise points: 150
- Number of clusters: 3

The script visualizes the clusters and labels the customers based on their cluster membership.

## 🌐 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♂️ Author

- **Your Name**  
  GitHub: [@your-username](https://github.com/your-username)
```

### Key Sections in the README:
1. **Project Overview** with clustering details.
2. **Installation Instructions** for dependencies.
3. **How to Clone and Run** the repository.
4. **Results and Output Examples** from clustering.
5. **License and Author** sections.

Feel free to modify and personalize the content based on your specific details, including your GitHub username, license type, and any additional project information!
