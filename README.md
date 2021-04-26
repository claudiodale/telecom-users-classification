# telecom-users-classification

Kaggle Telecom users dataset

url: https://www.kaggle.com/radmirzosimov/telecom-users-dataset 

the challenge is to spot churners….customers who will not renew their contract

I decided to choose the final algorithm taking into consideration the recall for the class “1” (churners).
If someone is a churner I want the algorithm to spot it …in this way the company can put in place strategies to prevent the customers from not renewing the contract.

The best result I got was through Logistic Regression (0.57 for recall class1 and 0.65 for precision for class 1).

The model is slightly overfitting which may create some uncertainty in terms of future predictions results
