
# Customer Segmentation

This project aims to segment customers based on marketing campaign data using clustering techniques. The goal is to help businesses understand their customers better and target specific segments with personalized strategies.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Approach](#approach)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [License](#license)

## Overview
Customer segmentation is a powerful tool for businesses to tailor marketing efforts by categorizing customers based on behavior and demographics. In this project, various clustering algorithms are applied to marketing campaign data to group customers effectively.

## Dataset
The dataset used for this project is `marketing_campaign.csv`, which includes the following key features:
- `ID`: Unique identifier for each customer.
- `Age`: Customer's age.
- `Education`: Customer's education level.
- `Marital_Status`: Marital status of the customer.
- `Income`: Annual income of the customer.
- `Kidhome`: Number of small children in the household.
- `Teenhome`: Number of teenagers in the household.
- `Recency`: Number of days since the last purchase.
- `MntWines`: Amount spent on wine in the last 2 years.
- `MntFruits`: Amount spent on fruits in the last 2 years.
- `MntMeatProducts`: Amount spent on meat products in the last 2 years.
- `MntFishProducts`: Amount spent on fish products in the last 2 years.
- `MntSweetProducts`: Amount spent on sweets in the last 2 years.
- `MntGoldProds`: Amount spent on gold products in the last 2 years.
- `NumDealsPurchases`: Number of purchases made with a discount.
- `NumWebPurchases`: Number of purchases made through the company’s website.
- `NumCatalogPurchases`: Number of purchases made using a catalog.
- `NumStorePurchases`: Number of purchases made directly in stores.
- `NumWebVisitsMonth`: Number of visits to the company’s website in the last month.
- `AcceptedCmp1` to `AcceptedCmp5`: 1 if the customer accepted the offer in the respective campaign, 0 otherwise.
- `Response`: 1 if the customer accepted the last campaign, 0 otherwise.

## Approach
1. **Data Cleaning**: Addressing missing values and correcting any data inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Understanding patterns and relationships in the data using various visualizations.
3. **Feature Engineering**: Creating relevant features based on existing data to enhance model performance.
4. **Clustering Algorithms**:
   - KMeans clustering
   - Hierarchical clustering
   - DBSCAN (Density-Based Spatial Clustering)
5. **Model Evaluation**: Using metrics like silhouette score and visual inspection to evaluate the performance of the clustering models.

## Installation
To get started with this project, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/your-username/Customer-Segmentation.git
cd Customer-Segmentation
pip install -r requirements.txt


## Usage
Run the Jupyter notebook to see the analysis and clustering results:

```bash
jupyter notebook Customer\ Segmentation.ipynb
```

Make sure to place the `marketing_campaign.csv` file in the project directory before running the notebook.

## Results
The results show distinct customer segments based on purchasing behavior, recency, and other factors. These segments can help businesses create targeted marketing campaigns for specific customer groups.

### Key Insights:
- High-income customers tend to purchase luxury products like wine and gold.
- Households with children show different purchasing patterns compared to households without children.
- Recency plays a critical role in determining which customers are more likely to respond to marketing campaigns.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Scikit-learn** (for clustering algorithms)
- **Pandas & NumPy** (for data manipulation)
- **Matplotlib & Seaborn** (for data visualization)
