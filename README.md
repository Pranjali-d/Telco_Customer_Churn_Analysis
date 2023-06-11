# Telco Customer Churn Analysis

![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) 
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346.svg?style=for-the-badge&logo=Microsoft-Excel&logoColor=white) 
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF.svg?style=for-the-badge&logo=Kaggle&logoColor=white)

</br>

## Overview
An interactive dashboard to represent some analysis of "Telco customer churn" data and the reasons that made customers churn using Microsoft Power BI.

</br>

##  Architecture 
![image](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/d4c9d38d-2f6c-43e2-81ca-3b5dc64a533b)

</br>

## About Dataset:

- **Telco customer churn:** This sample data module tracks a fictional telco company's customer churn based on a variety of possible factors. The churn column indicates whether or not the customer left within the last month. Other columns include gender, dependents, monthly charges, and many others with information about the types of services each customer has.

- **Source:** IBM.

- **The Telco customer churn data module is composed of 5 tables:**

    - Demographics
    - Location
    - Population
    - Services
    - Status

- **These tables are separated into multiple files:**

    - ```Telco_customer_churn_demographics.xlsx```
    - ```Telco_customer_churn_location.xlsx```
    - ```Telco_customer_churn_population.xlsx```
    - ```Telco_customer_churn_services.xlsx```
    - ```Telco_customer_churn_status.xlsx```

**You can know more about the dataset here:** 

[Telco customer churn (11.1.3+)](https://www.kaggle.com/datasets/ylchang/telco-customer-churn-1113)

</br>

## Data Modeling:

A star schema model is built for a faster-analyzing process.
The Telco Customer Churn Star Schema Model contains: 
- **One fact table:**
    - ```Telco_Churn_Fact```
- **Four dimensions tables:**
    - ```Services_Dim```
    - ```Demographics_Dim```
    - ```Location_Dim``` which contains sub-dimension ```Population_Dim```
    - ```Status_Dim```

![DataModel](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/06359047-5db6-474e-80ab-e2126362375f)

</br>

## Dashboard Preview :

The dashboard consists of multiple pages, and each page provides an analysis of a specific topic for better visualization, in addition to an overview page which provides a summary of the dataset and KPIs about the whole dashboard.

A filter that filters the whole dashboard based on the customer status is used for a better understanding of the customers' behavior and analyzes each and its results separately.



### Home Page </p>
which provides a summary description of the data, KPIs overview, and navigations to dashboard parts.
![1](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/cae8d86e-f1f1-4b56-9313-ea44748f4e4a)

</br>

### General Insights Page </p>
which provides a general analysis of the customers, their behavior, and the churn reasons.
![2](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/585c284a-9e24-44e6-8abc-c9994eab8acf)

</br>

### Customer Demographics Page </p> 
which analyzes the customers' demographics based on gender and age.
![3](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/93dcb0df-71e3-42b2-b508-24e45c633896)

</br>

### Service and Contract Page </p>
which analyze the services that customers subscribed to, services types, contract types, and all related topics.
![4](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/2d62738e-b4d2-4429-a87d-1f1d821215a0)

</br>

### Churn and Revenu Page</p>
which analyzes the revenue from each customer type, customers' states at the end of the year, churned customers, and their reasons to churn.
![5](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/assets/49934575/1d9cf769-23a7-4689-b69a-665f45908a7f)

</br>

## Resources
You can access all stages from designing background to calculation details of the prepared report [here](https://github.com/Pranjali-d/Telco_Customer_Churn_Analysis/tree/main/Resources).



