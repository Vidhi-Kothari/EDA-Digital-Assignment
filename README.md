# EDA-Digital-Assignment
This project focuses on performing a comprehensive analysis on a dataset containing student information, including their SAT scores, study hours, high school performance, and college GPA. The dataset is used to explore the relationships between these features and predict academic success, particularly in terms of college GPA. The analysis follows a structured approach, applying various statistical and machine learning techniques, ensuring a detailed understanding of the data and providing actionable insights.

**COLAB LINK**: https://colab.research.google.com/drive/1DlZOPjtQS9nfpfapgQgC5XIk5TuVUYsI?usp=sharing
## Dataset Overview
The gpa2.csv dataset contains the following columns:

- **sat**: SAT score of the student. <br>
- **tothrs**: Total hours spent studying.<br>
- **colgpa**: College GPA of the student.<br>
- **verbmath**: Verbal math score.<br>
- **hsize**: High school size.<br>
- **hsrank**: High school rank.<br>
- **hsperc**: High school percentile.<br>
- **female**: Whether the student is female (binary).<br>
- **white**: Whether the student is white (binary).<br>
- **black**: Whether the student is black (binary).<br>
- **hsizesq**: High school size squared.<br>

## Project Structure
The project is divided into several key tasks:

**1. Data Loading and Preprocessing**
- Loaded the dataset and inspected its structure.
- Cleaned the dataset by handling missing values and removing columns that were irrelevant for analysis.
- Standardized numerical features to ensure uniform scaling for modeling.

**2. Exploratory Data Analysis (EDA)**
- **Univariate Analysis**: Analyzed individual features, including measures of central tendency and dispersion. Plotted histograms, boxplots, and density plots for key features.
- **Bivariate Analysis**: Investigated relationships between pairs of variables using scatter plots, violin plots, and correlation heatmaps to uncover any significant patterns or correlations.
- **Multivariate Analysis**: Implemented scatter plots with multiple features and colors, facet grids, and bubble plots to visualize how different academic factors influence GPA.

**3. Time Series Analysis (Adapted for Dataset)**
- Although the dataset is not time-series, some tasks were adapted, including plotting and analyzing trends in the data.

**4. Clustering**
- **Hierarchical Clustering**: Applied hierarchical clustering to group similar students based on their academic factors. Visualized the dendrogram to analyze the formation of clusters.
- **K-Means Clustering**: Performed K-means clustering to group students into different clusters based on academic performance. Evaluated the optimal number of clusters using the Elbow Method and visualized the results.

**5. Principal Component Analysis (PCA)**
- Performed PCA to reduce dimensionality and explore how the most important features contribute to the variation in the data.
- Visualized the first two principal components to observe how they capture the underlying patterns in the data.

**6. Predictive Modeling**
- **Linear Regression**: Applied simple and multiple linear regression models to predict GPA based on various features like SAT scores, study hours, and high school academic performance.
- **Logistic Regression**: Applied logistic regression to classify students into high or low GPA categories, using features like SAT scores to predict the probability of achieving a high GPA.

**7. Visualizations**
- All visualizations were created with clarity and aesthetics in mind, ensuring proper labeling of axes and titles.
- Plots include histograms, scatter plots, regression lines, and logistic regression S-curves, among others, to help interpret the results.

## Conclusion
This project demonstrates the application of various statistical and machine learning techniques to analyze a dataset focused on predicting college GPA. The findings from the exploratory data analysis, clustering, and predictive modeling provide valuable insights into the factors that contribute to academic success. These insights can inform educational strategies and help students understand how to improve their GPA based on key performance indicators.
