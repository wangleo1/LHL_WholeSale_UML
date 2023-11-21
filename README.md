# LHL_Wholesale_UML

### Overview
This project aims to utilize unsupervised machine learning techniques to segment consumers within the Wholesale dataset. The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 

## Exploratory Data Analysis (EDA)

- Conducted EDA to gain insights on Wholesale_Data.csv dataset
- Explored missing values, correlations, data distributions, class imbalances and potential outliers
- Generated insights on data through visualization and statistical summaries

## Data Preprocessing

- Identified skewed data amongst the numeric columns
- Identified potential outliers
- Decided against altering data as it would alter the interpretation of consumer segments

## Cluster Analysis/Findings

- K-Means:
    - Identified optimal number of clusters utilizing the Elbow Method
    - Created consumer segments based on purchasing habits
- Hierarchical Model
    - Identified optimal number of cluster utilizing denrograms
    - Segmented consumers based on total spending

## Principal Component Analysis
- PCA was conducted to understand the underlying structure of the data and to identify the optimal number of features/reduce dimension

## Results
- Elbow Method and Dendrogram analysis resulted in different optimal clusters
    - K-Means, which utilized the Elbow Method, resulted in clusters k = 5
        -Segmenting consumers based on purchasing habits
    - Hierarchy clustering, which utilized Dendrogram analysis, resulted in cluster k = 2

- Different methods/algorithms resulted in different optimal clusters due to their methods of computation 
- PCA identified the optimal number of features to be 5
    - Five features would account for 95% of the variations within the model

## Future Goals
- Further hyperparameter tuning
- Attempt DBScan clustering 
- Deployment of generated models for real-world predictions
