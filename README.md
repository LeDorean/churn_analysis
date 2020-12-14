# churn_analysis

## About
For this project I gathered my data from https://www.kaggle.com/becksddf/churn-in-telecoms-dataset <br>
This dataset has 3333 instances of 20 descriptive features and 1 target variable.<br>
<u>Descriptive features</u>:<br>
   >state                   
    account length            
    area code                 
    phone number              
    international plan        
    voice mail plan           
    number vmail messages     
    total day minutes         
    total day calls           
    total day charge         
    total eve minutes         
    total eve calls           
    total eve charge          
    total night minutes       
    total night calls        
    total night charge       
    total intl minutes        
    total intl calls          
    total intl charge         
    customer service calls 


<u>Target variable</u>
>churn

This repo contains three folders.<br>
data: Has the original file as 'SyriaTel_customer_data', preproccessed file, and additional features<br>
notebooks: has two notebooks 'EDA' and 'Modeling'<br>
graphs_and_images: all the important graphs created in the notebooks<br>

## Goal

The goal for this project is to determine what leads customers astray and to predict if a customer will leave.

## A look inside
In this dataset we have a churn rate close of approx 15%
<img src="graphs_and_images/pie_chart_of_churn_rate.png">

Five states with highest churn rate
<img src="graphs_and_images/top_five_states_by_churnRate.png">

Churn rate is higher for customers with a international plan. Roughly 10% of customers use this feature.
<img src="graphs_and_images/churn_by_intl_plan.png">

## Hypothesis testing

The distribution of Total charges is different for the churned customers as viewed here.
It seems that customers who pay more than 80 are more liklely to leave.

<img src="graphs_and_images/pdf_total_charges.png">

The proportion of customers who leave us is greater than those who don't for the subset of customers who call customer service more than 4 times
<img src="graphs_and_images/pdf_customer_service_calls.png">

