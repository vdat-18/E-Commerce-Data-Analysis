# Tiki E-commerce Data Analysis

This repository contains data and code for analyzing e-commerce data from the Tiki.vn platform, incorporating frequent itemset mining techniques to enhance clustering outcomes.

## 📁 Folder Structure

### Data
The `Data` folder includes cleaned and raw datasets used in the project:
- **data_cleaned.xlsx**: A consolidated and cleaned dataset, created by merging and processing raw data files for analysis.
- **product_info.xlsx**: Raw data containing product information from various stores.
- **stores_info.xlsx**: Raw data containing information about each store.

### Code
The `Code` folder contains Jupyter notebooks covering the complete workflow, from data scraping to advanced analysis:
- **Data_Scraping_(Tiki).ipynb**: Contains code for scraping data from Tiki.vn and basic preprocessing steps.
- **Data_Preprocessing_(Tiki).ipynb**: Includes detailed data preprocessing, including noise reduction and feature transformation.
- **Data_Analysis_(Tiki).ipynb**: Covers data analysis and unsupervised learning algorithms to extract insights, integrating maximal frequent itemset mining.

## 🚀 Project Workflow

1. **Data Collection**: Gathered store data using web scraping on Tiki.vn.
2. **Data Preprocessing**:
   - **Cleaning**: Removed duplicates and handled missing or inconsistent values.
   - **Normalization**: Applied feature scaling for consistency.
   - **Outlier Management**: Reduced noise using Winsorization, Isolation Forest, and DBSCAN.
3. **Feature Engineering**:
   - Integrated binary features using the FP-Max algorithm, transforming continuous attributes into binary ones for clustering.
4. **Clustering**:
   - Evaluated algorithms like **K-Means**, **Gaussian Mixture Models (GMM)**, and **Agglomerative Clustering**, before and after integrating frequent itemset-based features.
5. **Model Evaluation**:
   - Metrics such as **Silhouette Score**, **Davies-Bouldin Index**, and **Calinski-Harabasz Index** were used to assess clustering quality.

## 📈 Analysis Workflow

1. **Exploratory Data Analysis (EDA)**: Identified trends and patterns within the dataset.
2. **Frequent Itemset Mining**: Enriched datasets with binary features derived from frequent patterns using FP-Max.
3. **Clustering and Comparison**:
   - Assessed clustering algorithms before and after binary feature integration.
   - Enhanced evaluation using mixed data analysis tools like Gower distance.
4. **Insights**:
   - Identified store segments with distinct characteristics, providing actionable recommendations for improving business strategies.

## 📝 Key Findings

- Adding binary features derived from FP-Max significantly improved clustering quality.
- Enhanced clusters provide deeper insights into store segmentation, enabling better strategy development for e-commerce platforms like Tiki.
