# Customer Data Analysis and Segmentation

## Script Overview

This Python script performs end-to-end customer data analysis and segmentation. The workflow includes:

1. **Data Generation**: Creates synthetic customer data including `customer_id`, `total_spent`, `purchase_count`, `avg_session_time`, and `last_purchase_date`.
2. **Data Saving**: Saves the generated data to a CSV file.
3. **Data Loading and Preprocessing**:
   - Loads data from the CSV file.
   - Handles missing values.
   - Scales features for clustering.
4. **Clustering**:
   - Applies KMeans clustering to segment customers into three distinct groups based on spending and purchase frequency.
5. **Visualization**:
   - Creates a scatter plot to visualize customer segmentation.
6. **Marketing Campaign**:
   - Simulates sending marketing emails to high-value customers (customers in the primary cluster).

## Challenges and Justifications

1. **Data Generation**: Creating synthetic data that accurately represents real-world scenarios can be challenging. Ensuring diversity and realism in generated data is crucial for meaningful analysis.

2. **Data Preprocessing**: Proper handling of missing values and scaling of features are essential for effective clustering. These steps are necessary to ensure the clustering algorithm performs optimally and avoids biases.

3. **Clustering**: Determining the number of clusters (3 in this case) can be subjective. This decision is based on domain knowledge and exploratory methods like the Elbow method. Adjustments may be needed based on actual data characteristics.

4. **Visualization**: Effective visualization helps in understanding the results of clustering. The scatter plot provides a clear view of how customers are segmented based on their spending and purchase behaviors.

5. **Marketing Campaign**: Simulating email sending requires accurate customer segmentation. The script targets high-value customers identified through clustering to optimize marketing efforts.

## Requirements

- `pandas==1.5.3`
- `scikit-learn==1.2.2`
- `seaborn==0.12.2`
- `matplotlib==3.7.1`
- `numpy`

## Usage

1. Ensure all required libraries are installed.
2. Run the script to generate data, perform analysis, and visualize results.
3. Review the output CSV file and the scatter plot for insights.
4. The script simulates sending marketing emails to high-value customers.

For further customization and enhancements, adjust the number of clusters, data generation parameters, or clustering features as needed.


