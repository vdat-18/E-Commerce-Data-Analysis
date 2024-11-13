# Tiki E-commerce Data Analysis
This repository contains data and code for analyzing e-commerce data from the Tiki.vn platform, from initial data scraping to final analysis and modeling.

## 📁 Folder Structure
### Data
The `Data` folder includes cleaned and raw datasets used in the project:
- **data_cleaned.xlsx**: A consolidated and cleaned dataset, was created by merging and processing the raw data files below. This file is ready for analysis.
- **product_info.xlsx**: Raw data containing product information across various stores.
- **stores_info.xlsx**: Raw data containing information about each store.
  
### Code
The `Code` folder contains Jupyter notebooks covering the complete workflow, from data scraping to advanced data analysis:
- **Data_Scraping_(Tiki).ipynb**: Contains the code for scraping data from Tiki.vn, along with basic data preprocessing steps.
- **Data_Preprocessing_(Tiki).ipynb**: Includes comprehensive data preprocessing to create a clean, analysis-ready dataset.
- **Data_Analysis_(Tiki).ipynb**: Contains data analysis and unsupervised learning algorithms to derive insights from the data.

## 🚀 Project Workflow
1. **Data Collection**: Gathered data using web scraping on Tiki.vn.
2. **Data Preprocessing**: Cleaned and transformed data into a suitable format for analysis.
3. **Data Analysis and Modeling**: Analyzed data and applied unsupervised learning techniques to extract insights.

## 📈 Analysis Workflow
Once the data was cleaned and ready for analysis, the following steps were undertaken to extract meaningful insights:
1. **Exploratory Data Analysis (EDA)**: Conducted a comprehensive EDA to uncover key trends and patterns within the dataset, laying the foundation for deeper analysis.
2. **Reliability Assessment**: Applied the Wilson Interval to assess and verify the reliability of information across stores, ensuring consistency and dependability.
3. **Outlier Management**:
   - **Noise Reduction**: Implemented Winsorization to minimize noise within the dataset.
   - **Outlier Removal**: Utilized the Isolation Forest algorithm to detect and remove primary outliers. Additionally, applied the DBSCAN algorithm for a thorough review, identifying and addressing any remaining outliers.
4. **Feature Selection**:
   - **FP-Max** and **Forward Selection** methods were employed to identify and select high-impact features, enhancing the clustering process by focusing on the most relevant attributes.
5. **Clustering Algorithms Comparison**:
   - Evaluated the performance of various clustering algorithms, including **K-Means**, **Gaussian Mixture Models (GMM)**, and **Agglomerative Clustering**.
   - Comparison was conducted both before and after the addition of frequent itemsets to observe their effect on clustering results.
6. **Results and Insights**:
   - Analyzed the outcomes and provided actionable insights to address the core objectives of the project, offering valuable guidance for decision-making.
   
## 🚧 Project Status
This project is currently in progress. Additional analysis, refinement, and documentation are ongoing as we continue to enhance insights and methodologies. Stay tuned for updates as we delve deeper into clustering techniques and feature selection for optimal results.


