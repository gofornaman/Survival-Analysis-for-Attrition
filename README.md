# Survival-Analysis-for-Attrition
Using Survival Analysis (Lifelines) to build a Customer Attrition Model

1. Objective
  - Customer Attrition or Churn refers to a decision made by the customer about ending the business relationship.
  - Customer loyalty and customer churn always add up to 100%. If a firm has a 60% of loyalty rate, then their loss or churn rate of customers is 40%.
  - Churn is undesirable and it is the firm's responsibility to understand why customers are churning and prevent that

2. Approach
  - Usually when it comes to Predicting customer churn, we look at classification techniques such as Logistic regression but the problem with that approach is that it doesn't take time into consideration
  - So we will be using a tool from an unlikely place - Survival analysis. It was first developed by actuaries & medical professionals to predict survival rates

    Here we will be defining -
        Birth event: For eg, a customer subsribing to your product or service
        Death event: For eg, a customer ending the relationship with the company

    Component that makes SA superior to other models is its ability to deal with "censorship" in data
    Censorship basically refers to losing track of a customer or the customer "not dying" before the end of the observation period
    This data is considered "censored" since everyone dies eventually, we are just missing the data
    Similarly, we would expect to lose all customers eventually. Just because we haven't observed them cancelling their subscription doesn't mean they never will.

We have all come across "Teleco Customer Churn" dataset which we usually use to Predict customer churn by binary classification method.
Now, we will use the same dataset and apply our newly learnt Survival analysis skills.

![Kaplan-Meier Survival Curve](https://github.com/gofornaman/Survival-Analysis-for-Attrition/blob/main/img/S1.PNG)
