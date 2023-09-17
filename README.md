
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
|Medium   |                          |  [ Best article to gain machine-learning insights                        ](/) |

## Project Description

-  This is a time series forecasting problem. In this project, we predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.Specifically, we are to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores.

## Exploratory Data Analysis: EDA

### Univariate Analysis 

![Alt text](images/univariatechurn.png)

![Alt text](images/univariategender.png)

![Alt text](images/univariateinternetservice.png)

![Alt text](images/univariatepayment.png)

![Alt text](images/univariatetotalcharges.png)

### Multivariate Analysis 

![Alt text](images/multivariate.png)

## Hypothesis development 

✨ NULL: Contract type does not influence customer churn

✨ ALTERNATE: Contract type affects customer churn

based on chi-square test, we observe that the p-value is less than alpha, hence we reject Ho and conclude that is there is a statistical significance association between Churn and Contract.

## Business questions
1. How does gender impact customer churn? 

![Alt text](images/bivariategender.png)

2. Does the presence of a partner or dependents influence customer churn? 

![Alt text](images/bivariatepartnerdependents.png)

3. How does the length of tenure affect churn rates? 

![Alt text](images/bivariatetenure.png)

4. What role do additional services (e.g., online security, tech support, streaming TV, etc.) play in reducing customer churn? 

![Alt text](images/bivariateadditionalservices.png)

5. Is there a correlation between the contract term (month-to-month, one year, two years) and churn rates? 

![Alt text](images/bivariatecontract.png)

## Setup

Follow these steps to set up the project on your local machine:

1. **Clone the repository:**
   git clone https://github.com/your-username/Telco-Churn-Analysis.git

2. Navigate to the project directory:
  cd Telco-Churn-Analysis

3. Install required dependencies:
  pip install -r requirements.txt

4. Download the dataset:
  Download the Telco Churn dataset from the datasets folder and place it in the data directory. 

5. Run the analysis:
  Depending on your preferred IDE or notebook environment, open and run the provided Jupyter Notebook or Python scripts. 

6. Evaluate models:
  After training and tuning models, evaluate them using the evaluation dataset. You can use the provided evaluation script or notebook.

7. Export the best model:
  If desired, export the best trained model using the provided export script.

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
- Open the provided Jupyter Notebook (Telco_Churn.ipynb) and follow the step-by-step guide to explore the dataset, visualize data, and gain insights.

2. Model Training and Tuning:
- Open the notebook to see how different machine learning models are trained, tuned, and evaluated for Telco Churn prediction.

3. Exporting the Best Model:
- If you want to export the best trained model, run the export script (export_best_model.py). The exported model can be loaded and used for predictions.

4. Using the Exported Model:
- Refer to the "App Execution" section in this README for instructions on how to load the exported model and make predictions on new data.

## Conclusions 

Random Forest Classifier emerged as the best model for predicting customer churn. This model demonstrated a robust ability to accurately predict whether a customer is likely to churn or not.

## Key Insights :chart_with_upwards_trend:

✨ Customer churn rate decreases with an increase in tenure :chart_with_upwards_trend:

✨ Availability of additional services plays a crucial role in reducing customer churn :chart_with_upwards_trend:

✨ customers on long-term contracts are less likely to churn compared to those on month-to-month contracts :chart_with_upwards_trend:


## Appreciation
-   I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about https://medium.com/@azubiafrica and take a few minutes to visit this link to learn more about Azubi Africa life-changing https://bit.ly/41CGCwK 

-  **Tags**

https://bit.ly/3ARq742


## Author

`Benedicta Mankata `

`Data Analyst`

`Azubi Africa`