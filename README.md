# Telecom-Churn
Predictive analytics for telecom customer churn

### Problem statement:
In the telecom industry, customers can choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
In this project, we analysed customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

### Steps:
•   Business Understanding 
•   Data Understanding & cleaning 
•   Data visualization and EDA 
•   Data Preparation 
•   Model Building
•	  Model Evaluation

### Findings:
The logistic regression model without Principal Component Analysis (PCA) demonstrates favourable sensitivity and accuracy, akin to models incorporating PCA, according to the current analysis. Consequently, choosing the simpler logistic regression model without PCA is warranted. This model not only elucidates key predictor variables but also underscores the significance of each variable. It assists in pinpointing the vital variables essential for decision-making regarding potential churned customers. Thus, this model holds greater relevance in conveying insights to the business.

### Business recommendation:		
1.	Focus on customers whose Minutes of Usage (MOU) for incoming local calls and outgoing ISD calls have decreased, particularly in the action phase, mostly observed in the month of August.
2.	Identify customers with lower outgoing charges for other services in July and reduced incoming charges for other services in August.
3.	Target customers experiencing an increase in Value-Based Cost (VBC) during the action phase, as they are more likely to churn. Consider offering incentives to retain this segment.
4.	Customers with a higher monthly 3G recharge in August are at a higher likelihood of churning.
5.	Look out for customers witnessing a decline in STD incoming Minutes of Usage (MOU) for operators in August, as they are more prone to churn.
6.	Customers with a decreasing monthly 2G usage in August are also expected to churn.
7.	Identify customers with decreasing incoming MOU in August, as they show a higher likelihood of churning.
8.	Pay attention to the "roam_og_mou_8" variable, where positive coefficients (0.7135) indicate that customers with increasing roaming outgoing minutes of usage are more likely to churn.


