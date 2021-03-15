Assignment 1: Supervised Learning
gatech user_name: vraja30

Data sources:

Folder location: https://github.com/vinayakraja/cs7641/tree/main/assignment-1

Data 1: Customer propensity to purchase dataset

This data set represents a day's worth of visit to a fictional website. Each row represents a unique customer, identified by their unique UserID. The columns represent feature of the users visit (such as the device they were using) and things the user did on the website in that day. These features will be different for every website, but in this data a few of the features we consider are:

    basketadddetail: Did the customer add a product to their shopping basket from the product detail page?
    sign_in: Did the customer sign in to the website?
    saw_homepage: Did the customer visit the website's homepage?
    returning_user: Is this visitor new, or returning?
    In this data set we also have a feature showing whether the customer placed an order (ordered), which is what we predict on.

Link to data source: https://www.kaggle.com/benpowis/customer-propensity-to-purchase-data

Data 2: Telcom Customer Churn

The data set includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

Link to data source: https://www.kaggle.com/blastchar/telco-customer-churn

Running code: 

The data is stored as CSV in data folder in the repo and has two Jupyter notebooks with corresponding analysis.

Jupyter-notebooks:
1. customer_purchase_propensity.ipynb - contains all analysis and models for first dataset where our goal is to predict who is likely going to purchase based on site interaction and actions. 

2. telecom_churn.ipynb - contains all analysis and models for second dataset where our goal is to predict who is likely going to churn for this telecom provider based on demographic and account information. 

**All results and analysis already saved as cell output in these notebooks.

Repository link: https://github.com/vinayakraja/cs7641.git


How to run:
1. Clone repository from github : https://github.com/vinayakraja/cs7641.git
2. I have added all dependencies in requirements.txt and added this in 'pip3 install -r requirements.txt' in notebook
3. open Jupyter notebook in Python 3.7 enviornmnet:
     1. In order to re-create everything end to end click on CELLS and clink Run All ( this will take time as we do HP tnining for various algos) 
     2. in order to run individual code blocks, pressing shift + enter