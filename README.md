Wine Quality Analysis
This project analyzes a dataset of red and white wine samples to classify wine types and quality levels based on chemical properties.

Dataset
The dataset contains measurements of 13 chemical properties for 6,497 wine samples, including:

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol
Quality rating (3-9)
Wine type (red or white)
Analysis
The analysis includes:

Data cleaning and outlier removal
Exploratory data visualization
Principal component analysis (PCA)
Factor analysis
Key Findings:
4 principal components explain ~76% of variance
PC1 separates red and white wines
PC2 correlates with quality ratings
A single factor explains 82% of variance, related to wine preservation
Usage
The analysis is implemented in R. To reproduce:

Install required R packages (listed in code)
Run the R script
View generated plots and output
Future Work
Potential extensions:

Apply machine learning models for wine classification
Analyze additional wine datasets for comparison
Investigate non-linear relationships between variables
References
Data source: UCI Machine Learning Repository - Wine Quality Dataset# Wine
 
