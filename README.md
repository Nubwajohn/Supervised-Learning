# Supervised Learning
Project: ReCell

### Project Overview

Predicting Prices of Used Phones and Tablets: Analyze the used device dataset, build a model that helps develop a dynamic pricing strategy for used and refurbished devices, and identify factors that significantly influence the price.

### Data Sources

The primary dataset utilized for this analysis is the “used_device_data.csv” file, which contains a range of attributes related to used and refurbished phones and tablets. The data was collected in 2021, providing valuable insights into various factors that influence device pricing and demand during that period.

### Tools

- Programming Language: Python.
- Data Manipulation & Analysis Libraries: Pandas, NumPy.
- Data Visualization Libraries: Matplotlib, Seaborn.
- Machine Learning Library: Scikit-Learn.
- Data Preprocessing & Exploratory Data Analysis (EDA) Tools:Excel, Google Colab.

### Import Necessary Libraries
**Chart**

### Data Overview

  The initial steps to get an overview of any dataset is to:
  - Observe the first few rows of the dataset, to check whether the dataset has been loaded properly or not.
  - Get information about the number of rows and columns in the dataset.
  - Find out the data types of the columns to ensure that data is stored in the preferred format and the value of each property is as expected.
  - Check the statistical summary of the dataset to get an overview of the numerical columns of the data.

### Exploratory Data Analysis (EDA)

- EDA is an important part of any project involving data.
- It is important to investigate and understand the data better before building a model with it.
- A few questions have been mentioned below which will help you approach the analysis in the right manner and generate insights from the data.
- A thorough analysis of the data, in addition to the questions mentioned below, should be done.

**Questions:**
1. What does the distribution of normalized used device prices look like?
2. What percentage of the used device market is dominated by Android devices?
3. The amount of RAM is important for the smooth functioning of a device. How does the amount of RAM vary with the brand?
4. A large battery often increases a device's weight, making it feel uncomfortable in the hands. How does the weight vary for phones and tablets offering large batteries (more than 4500 mAh)?
5. Bigger screens are desirable for entertainment purposes as they offer a better viewing experience. How many phones and tablets are available across different brands with a screen size larger than 6 inches?
6. A lot of devices nowadays offer great selfie cameras, allowing us to capture our favorite moments with loved ones. What is the distribution of devices offering greater than 8MP selfie cameras across brands?
7. Which attributes are highly correlated with the normalized price of a used device?

### Data Preprocessing

- Missing value treatment
- Feature engineering 
- Outlier detection and treatment
- Preparing data for modeling
- Any other preprocessing steps 

### Model Building - Linear Regression
**chart**

### Model Performance Check
**Let's check the performance of the model using different metrics.**
- Using metric functions defined in sklearn for RMSE, MAE, and  R2.
- Define a function to calculate MAPE and adjusted  R2 .
- Create a function which will print out all the above metrics in one go.

### Checking Linear Regression Assumptions
- In order to make statistical inferences from a linear regression model, it is important to ensure that the assumptions of linear regression are satisfied.

**We will be checking the following Linear Regression assumptions:**
1. No Multicollinearity
2. Linearity of variables
3. Independence of error terms
4. Normality of error terms
5. No Heteroscedasticity
   
### Predictions On Test Data
**Now that we have checked all the assumptions of linear regression and they are satisfied, let's go ahead with prediction.**
 **chart**
 
### Final Model
**chart**

### Actionable Insights and Recommendations
