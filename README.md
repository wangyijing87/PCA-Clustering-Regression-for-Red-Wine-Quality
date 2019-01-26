# PCA-Clustering-Regression-for-Red-Wine-Quality

We will use the publicly available red wine quality dataset from the UCI Machine Learning Repository to perform our analysis. The dataset contains 1599 instances with 12 attributes for red variants of the Portuguese "Vinho Verde" wine.  

The following analytical approaches are taken in our analysis:
● Data Preparation: Prepare raw data for analysis  
● Principal Component Analysis (PCA): Perform dimension reduction techniques to identify a new set of orthogonal variables  
● Cluster Analysis: Classification of wines based on physicochemical properties  
● Regression Analysis: Prediction of quality ranking from the chemical properties of the wines using Ordinal Multinomial Logistic Regression  

#### Data Preparation
The red wine quality dataset contains 1599 instances with 11 physicochemical features (density, pH level, alcohol, etc.) and 1 sensory variable (quality). The physicochemical features are all continuous and the sensory variable is ordinal, with 0 being the worst and 10 being the best. Each sample of wine was evaluated by a minimum of three sensory assessors through blind taste test, and a score was given. The median of these evaluation scores was recorded as the final sensory quality score. In our dataset, quality scores range from the 3, the lowest, to 8, the highest.  

The correlation table below shows that some of the attributes have ±0.5 correlation coefficient with each other, indicating that there may be some underlying linear relationships among these attributes. Hence, PCA is appropriate in this case to identify a set of uncorrelated components to reduce dimension in order to build a better predictive regression
model.
Before
