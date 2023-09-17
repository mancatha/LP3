
# Regression Project

# Analysis of External Factors that Impact Sales of a Retail Store- A Regression Analysis
# Introduction
 In the highly competitive landscape of the retail industry, understanding the multifaceted dynamics that influence sales performance is essential for strategic decision-making. External factors, ranging from economic indicators and seasonal trends to marketing efforts and competitive influences, play a pivotal role in shaping a retail store's sales trajectory. Through a comprehensive regression analysis, this study aims to delve into the intricate relationships between these external variables and sales outcomes. By quantifying the impact of these factors, retailers can glean actionable insights to optimize operations, tailor marketing strategies, and ultimately enhance their revenue-generation potential.

# Objective
 The objective of this study is to investigate how external factors such as holiday events, oil prices, public sectors wages and natural occurences, impact the sales of Corporation Favorita, a large Ecuadorian-based grocery retailer.

# Hypothesis

### Null Hypothesis: Promotions have no significant effect on product sales.

### Alternate Hypothesis:  Promotions positively impact product sales, leading to increased sales during promotional periods.

-  *Attached are articles to my project with more information.*
## Summary
| Article     | Links      | Description |
|-----------|-------------|:-------------:|
|Power BI| https://app.powerbi.com/links/5LxtH6Lx02?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare  |  [Interactive dashboard](/) |
|Medium   |   https://medium.com/@benmanks2015/the-external-factors-that-impact-sales-of-a-retail-store-a-regression-model-33725e0f9154                       |  [ Best article to gain machine-learning insights                        ](/) |

## Project Description

-  This is a time series forecasting problem. In this project, we predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.Specifically, we are to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores.

## Exploratory Data Analysis: EDA

### Univariate Analysis

![](images/oil.png)

![](images/cities.png)

![](images/monthlysales.png)

![](images/monthlysales.png)

![](images/product.png)

### Multivariate Analysis 

![Alt text](images/salesandtransactions.png)

![Alt text](images/transactionbystores)

![Alt text](images/salesforholiday.png)

## Hypothesis development

✨ NULL:There is no correlation between sales and promotion (ρ = 0)

✨ ALTERNATE: There is a correlation between sales and promotions (ρ ≠ 0)

based on chi-square test, we observe that the p-value is less than alpha, hence we reject Ho and conclude that is there is a statistical significance association between Churn and Contract.

## Business questions
1. Does store size affect total sales?? 

![Alt text](images/cluster.png)

2. Did the earthquake impact sales?

![Alt text](images/earthquake.png)

3. Are sales affected by promotions?

![Alt text](images/promotedandnonpromoted.png)

4. What are the best-selling products?

![Alt text](images/product.png)

5.Which days have the most sales?

![Alt text](images/dayofsalesbyweek.png)



## App Execution

To use the exported best model for predictions:
1. Load the exported model:
In your Python script or notebook, load the saved model using pickle:
import pickle

with open('export/customer_churn_model.pkl', 'rb') as f:
  best_model = pickle.load(f)

2. Make predictions:
Use the loaded model to make predictions on new data:
new_data = ...  # Prepare your new data
predictions = best_model.predict(new_data)

3. Interpret predictions:
- Interpret the predictions according to your problem domain and make decisions based on the results.

## Usage

To use this project:

1. Exploratory Data Analysis:
- Open the provided Jupyter Notebook (LP3.ipynb) and follow the step-by-step guide to explore the dataset, visualize data, and gain insights.

2. Model Training and Tuning:
- Open the notebook to see how different machine learning models are trained,  and evaluated for sales prediction.



## Conclusions 

Random Forest Classifier emerged as the best model for predicting the best metrics for sales. By leveraging the insights gained from our analysis and following the recommendations, businesses can make informed decisions, optimize operations, and respond effectively to market dynamics and external events.



## Appreciation
-   I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about https://medium.com/@azubiafrica and take a few minutes to visit this link to learn more about Azubi Africa life-changing https://bit.ly/41CGCwK 

-  **Tags**

https://bit.ly/3ARq742


## Author

`Benedicta Mankata `

`Data Analyst`

`Azubi Africa`