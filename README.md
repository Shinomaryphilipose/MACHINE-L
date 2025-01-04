The given house_price.csv contains property prices in the city of Bangalore. I examined the price per square feet did the following: 
Performed basic EDA which includes acquring the data,importing all the necessary libraries like pandas,numPy,matplotlib.pyplot,seaborn etc.
Detected the outliers using following methods and remove it using methods like trimming / capping/ imputation using mean or median  
a) Mean and Standard deviation
b)Percentile method 
c) IQR(Inter quartile range method)
d) Z Score method
Created a box plot and used this to determine which method seems to work best to remove outliers for this data.
A histplotis created  to check the normality of the column(price per sqft column) and performed transformations if needed.
Checkedthe skewness and kurtosis before and after the transformation.
Checked the correlation between all the numerical columns and plot heatmap.  
Scatter plots are created between the variables to check the correlation between them.  
EDA AND PREPROCESSING
Employee.csv is the dataset used.
Objective:
The main objective of this project is to design and implement a robust data preprocessing system that addresses common challenges such as missing values, outliers, inconsistent formatting, etc. By performing effective data preprocessing, the project aims to enhance the quality, reliability, and usefulness of the data for machine learning.

Data Exploration is done by a) exploring the data, b)listed down the unique values in each feature and found its length.
c)Performed the statistical analysis and renamed the columns.

Data Cleaning is done with the following steps:
1.Found the missing and inappropriate values, treated them appropriately.
2.Removed all duplicate rows.
3.Found the outliers.
4.Replaced the value 0 in age as NaN
5.Treated the null values in all columns using any measures(removing/ replace the values with mean/median/mode)

Data Analysis is done with the following steps:
1.Filtered the data with age >40 and salary<5000
2.Ploted a sctterplot chart with age and salary
3.Count the number of people from each place and represent it visually

In Data Encoding Converted categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.

Feature Scaling: After the process of encoding, performed the scaling of the features using standardscaler and minmaxscaler.

REGRESSION:
 The objective of this assignment is to evaluate theunderstanding of regression techniques in supervised learning by applying them to a real-world dataset.
Used the California Housing dataset available in the sklearn library. This dataset contains information about various features of houses in California and their respective median prices.
Loaded the California Housing dataset using the fetch_california_housing function from sklearn.
Converted the dataset into a pandas DataFrame for easier handling.
Handled missing values (if any) and performed necessary feature scaling (e.g., standardization).
Explained the preprocessing steps performed and justified why they are necessary for this dataset.
Implemented the following regression algorithms:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
Evaluated the performance of each algorithm using the following metrics:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared Score (R²)
Compared the results of all models and identified:The best-performing algorithm andThe worst-performing algorithm. 


