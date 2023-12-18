# My-ML-projects
This repo contains several Data science and ML projects I've worked on
---

## Project 1 

customer segmentation and comprehensive analysis:


### Data Description:

The provided code is an analysis and modeling script for a Superstore dataset, aiming to help a Superstore Giant understand and optimize its operations. The dataset includes information such as Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, and Profit.

### Data Understanding:

The initial section of the code involves loading necessary libraries (Pandas, NumPy, Matplotlib, Seaborn) and reading the dataset from the provided link. The dataset is then displayed, and initial insights are gained through summary statistics, information on missing values, and data types.

Data cleaning steps include handling missing values, correcting data types (converting Order Date and Ship Date to datetime), and checking for duplication and outliers.

### EDA & Visualization:

The code explores univariate analysis, providing visualizations for various features such as Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Category, Sub-Category, Product Name, Sales, Quantity, Discount, and Profit. Histograms, bar plots, and other visualizations are used to understand the distribution and patterns within each feature.

### Bivariate and Multivariate Analysis:

The code delves into bivariate and multivariate analysis, answering questions like the top-selling and most profitable products, sales and profit trends over time, revenue and profit by category, region-wise sales, and the impact of discounts on sales. Visualizations, such as bar plots and line plots, aid in interpreting the relationships between different variables.

### Correlation Analysis:

Correlation analysis is performed, including a correlation matrix heatmap and a pair plot to visualize the relationships between numerical variables. This helps identify potential correlations between features.


### Data Preprocessing:

Feature engineering is applied to create a new feature, 'order_day', and unnecessary columns are dropped. Encoding is performed using one-hot encoding to convert categorical variables into a format suitable for machine learning models.

### PCA (Principal Component Analysis):

Principal Component Analysis is applied for dimensionality reduction. The code uses PCA to transform the encoded data into a lower-dimensional space (50 components) and outputs the explained variance ratio for each component.

### Modeling (Customer Segmentation):

The code utilizes the KMeans clustering algorithm for customer segmentation. Three clusters are created, and the results are visualized using scatter plots and bar plots to understand the distribution of Sales and Profit among different clusters.

Overall, this script provides a comprehensive analysis of the Superstore dataset, from data understanding and cleaning to exploratory data analysis, visualization, and modeling for customer segmentation.

