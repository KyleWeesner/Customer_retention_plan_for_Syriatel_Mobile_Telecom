# Customer retention plan for Syriatel Mobile Telecom
 
 
Author: Kyle Weesner
 
## Overview
Syriatel Mobile Telecom is a service pervider that currently serves more than 8 million people today having 199 international roaming partners in 116 countries.  As a data scientist, I am currently creating a model to predict when might customers churn.  By building a model to help predict when customers will deter away from the service I can either offer additional advice to for the company to allocate resources to make the customer happier and improve our services that may be not opitimal at the time.  This is a great way to see where improvements to the company may need to be done. 


## Business Problem
Service providers strive to maintain a healthy balance between gaining new customers while minimizing those who switch providers.  Syriatel provides service to more than 8 million people today and in our data set 15% of customers churned during this time period.  If this sample dataset somewhat resembles the total dataset this company has lost over a million customers.  As a business we want to maximize profit where it can be done without making unhappy customers, so one place this can be done is the retention rate of customers.  With our predictive model, we will improve features in our business that seem to have a correlation with leaving customers and at the same time offer additional support to customers who are considering leaving our service.  

 
## Data
For model building we used data from [Churn in Telecom's dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset) aquired from kaggle.  This data file is available in the project repo in the folder "data".  

 
## Tools
A productive model was made with a combination between the data and tools used in this project. 
- This report uses pandas for datafram manipulation and data analysis.  
- Sklearn for statistical modeling and machine learning.  

## Navigation

Follow through these notebooks in order that are located in the workspace folder in this repository

1. [Data Cleaning and Exploratory Data Analysis](./Data&#32;Cleaning&#32;and&#32;Exploratory&#32;Data&#32;Analysis.ipynb)

2. [Model Building](./Model&#32;Building.ipynb)

3. [Feature Importance Analysis](./Feature&#32;Importance&#32;Analysis.ipynb)

## Results
Model Proformance Metrics

![img]('./images/confusion_matrix')


Model Improvements

![img]('./images/model_improvement.jpg')


From the final model I looked at the feature importances and found that Customer Service Calls, Total Day Charge, and International Plan had the largest impact on our model. So based on my final model drew out these three instances.    


![img]('./images/customers_service_calls.jpg')


![img]('./images/customers_status_percentile_averages.jpg')


![img]('./images/retention_comparison_interrnational_plan.jpg')



## Conclusions

I would focus on improving customer service with priotizing keeping customer serrvice calls under 4.

Implement new payment plans per amount of data usage that are better cost efficient for the customer or have monthly plans. 

The current international plan needs to be evaluated and changed due to large proportion using end up leaving.
 
## Repository Structure
```
├── Jupyter Notebooks  
│       ├── Workspace_Kyle
│       │   └── Data_Exploration_Kyle.ipynb
│
├── data
├── images
├── README.md
└── Jupyter_Notebook_Final.ipynb
```
 
### Next Steps

     

## Citations:
