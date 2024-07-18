# ABC-Analysis
This project involved classifying products into A, B, and C categories based on their contribution to total sales value, aiming to optimize inventory management. The analysis steps were:

Data Loading and Cleaning: Loaded data from a CSV file and handled missing values.

Feature Engineering:
      Calculated the total sales value for each product.
      Sorted products by total sales value in descending order.
      Computed cumulative sales value and cumulative percentage for the sorted products.
      Classified products into categories A (top 70% of sales value), B (next 20% of sales value), and C (remaining 10% of sales value).
Visualization: Plotted a bar chart showing the number of products in each category.

Segmentation: Segmented the dataset into three categories (A, B, C) for further analysis and management.

Tools used included Pandas, NumPy, Seaborn, and Matplotlib in Python.
