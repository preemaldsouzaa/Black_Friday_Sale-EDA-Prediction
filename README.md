# Black_Friday_Sale-EDA-Prediction
Exploring Black Friday Sale data with EDA &amp; ML predictions 🛍️📈 Unlock insights, customer trends, and anticipate purchases. Let's dive into the shopping frenzy! 🛒🎯 #DataScience #ML #BlackFriday

## Introduction:
Black Friday is a shopping holiday held the day after Thanksgiving. It is well-known for offering huge discounts and great deals on a variety of things such as electronics, home goods, clothing, and more. On Black Friday, many businesses offer exceptional doorbuster prices and longer hours, and it is generally one of the busiest shopping days of the year.
The dataset we have consists of 537578 rows and 12 columns.
Our primary goal will be to conduct various types of analyses and draw conclusions znd predictions that will allow us to deliver important market insights and so benefit the firm.

## Business Problem:
The firm wants to gain important market insights and leverage the data from the Black Friday shopping event to make informed decisions and improve their business strategies. They aim to understand customer preferences, buying patterns, and the impact of demographics on purchase behavior. By conducting various analyses on the dataset, the firm aims to draw conclusions that will help them optimize their product offerings, target specific customer segments, and enhance their marketing efforts.
In addition to gaining market insights, the company also wants to leverage the data from the Black Friday shopping event to make predictions of customer purchases which will involve developing a machine learning model that can forecast whether a customer is likely to make a purchase during the Black Friday event based on various features such as demographics, product preferences, and buying patterns.

## Business Statement:
Our objective is to analyze the dataset from the Black Friday shopping event to uncover valuable market insights. By thoroughly cleaning and examining the dataset, we will investigate various columns such as gender, age, marital status, city category, occupation, and product categories. Through comprehensive analysis, we will identify trends, preferences, and correlations between these variables. Additionally, we will delve into multi-column analyses to gain a deeper understanding of how age, gender, marital status, and city category collectively impact shopping behavior. Furthermore, we will explore the relationship between customer loyalty, gender, and marital status, and investigate the influence of occupation on product preferences. Lastly, we will focus on analyzing product category 1 to determine its significance and potential opportunities for improvement. By combining gender and marital status, we aim to identify specific customer segments for targeted marketing initiatives. The findings from our analyses will provide important market insights to the firm, enabling them to make data-driven decisions and enhance their business strategies.

## Project Categories:
#### We are going to divide the project into 11 parts:
1. Dataset Cleaning
2. Analyzing Columns
3. Analyzing Gender
4. Analysing Age & Marital Status
5. Multi Column Analysis of Age, Gender, Marital Status and City Category
6. Customers Stay in Current City, Gender & Marital Status Analysis
7. Occupation and Products Analysis
8. Analysing Product Category 1
9. Combining Gender & Marital Status
10. Prepare the data for different Regression ML Models
11. Apply different types of ML Models with hyperparameter tuning to check which suits the best and gives accurate predictions.

## Exploratory Data Analysis Conclusions:
The insights made from the data visualisation as part of the Data Learning process are listed below:
1. Male customers make around 75% of all purchases, with female customers making the remaining 25%. This indicates that male users account for the majority of the commercial store's revenues. On average, males spend more money on purchases than females, and this trend may be observed by summing the total value of purchases.
2. We discovered that Unmarried Men spend the most on Black Friday when we coupled Purchase and Marital_Status for study. It also shows that men tend to spend less when they marry. It could be due of the increased obligations.
3. There is a fascinating column. Stay_In_Current_City_Years, after studying this column, we discovered that those who have lived in the city for one year likely to spend the most. This is comprehensible because people who have lived in the city for more than four years are often more established and less interested in buying new goods than people who are new to the city, who tend to spend more.
5. Surprisingly, when we examined which city the item was purchased in, we discovered that, while city B is mostly responsible for overall sales revenue, the aforesaid product was primarily purchased in city C.
4. For the Age feature, we discovered that consumers between the ages of 25 and 40 spend the most.

## Data Modeling/Processing:
In this project, we began by preparing the data for modeling. Unwanted columns, 'User_ID' and 'Product_ID', were dropped to eliminate unnecessary information. Categorical columns were encoded using LabelEncoder to convert string values into numeric format, enabling better processing by machine learning algorithms. Additionally, we addressed missing values in the 'Stay_In_Current_City_Years' column by converting the '4+' category to the numeric value 4. After preprocessing, the data was split into training and test sets with a 80-20 split ratio, where 80% of the data was used for training the models, and 20% for evaluating their performance.

## Applying ML Models:
Several machine learning models were applied to predict purchase amounts during the Black Friday shopping event. Linear Regression, Decision Tree Regressor, Random Forest Regressor, Lasso Regression, XGBoost Regressor, and CatBoost Regressor were trained and evaluated. Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-Squared Error were used as evaluation metrics. The CatBoost Regressor outperformed other models, achieving the lowest MAE and MSE, and the highest R-Squared Error. This indicates that the CatBoost Regressor's predictions were close to the actual purchase amounts and it explained a significant portion of the data's variance.

## Conclusions:
In conclusion, the CatBoost Regressor emerged as the most effective model for predicting purchase amounts during the Black Friday sale. It demonstrated the lowest errors and the highest R-Squared Error, indicating superior predictive performance and capturing a considerable portion of the data's variability. The model's insights can be leveraged by businesses to optimize product offerings, target specific customer segments, and enhance marketing strategies for future Black Friday events. Other models, such as Decision Tree Regressor and XGBoost Regressor, also displayed promising results, while Linear Regression and Lasso Regression had limitations in capturing the data's complexity and predicting purchase amounts accurately. Overall, data modeling, ML model application, and analysis provided valuable market insights to improve business strategies and enhance customer experiences during the Black Friday shopping event.
