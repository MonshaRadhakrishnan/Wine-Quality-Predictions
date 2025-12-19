# Wine-Quality-Predictions


This project explores the Wine dataset to understand how chemical properties differentiate wine classes (0, 1, 2). The focus is on identifying feature behavior, class overlap, and selecting appropriate machine learning models based on EDA insights.

1. Importing Libraries and Dataset
2. Data Sanity Checks
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Feature Engineering and Preprocessing
6. ML Model Selection
7. ML Model training and evaluation
8. ML Model interpreation and insights

**EDA**

Data inspection and validation (shape, types, missing values)
Target class distribution analysis
Univariate and bivariate analysis using histograms, boxplots, and swarmplots
Correlation analysis (overall and class-boundary focused)
Boundary-based analysis between class pairs (0–1 and 1–2)
Dimensionality reduction using PCA for visual inspection

**Key Insights**

Wine classes 0 and 2 show clear separation across multiple features
Class 1 overlaps significantly with both classes
Class 1 is not defined by a single dominant feature
On average, class 1 wines have lower alcohol, malic acid, magnesium, color intensity, and proline
Class 1 is characterized by a combination of moderate-to-low feature values rather than extremes
