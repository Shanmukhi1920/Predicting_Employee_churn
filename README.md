**Title**: Predicting Employee Turnover using Python

**Description**: Employee turnover is the process of employees leaving the company also known as employee attrition or employee churn. When skilled employees leave, this can be very costly for the company, thus firms are interested in predicting turnover beforehand. Having that information in hand, companies can change their strategy to retain good workers or start the hiring process of new employees on time.

**Data**: The data has 14999 samples and 17 columns which are: ('satisfaction', 'evaluation', 'number_of_projects','average_montly_hours', 'time_spend_company', 'work_accident', 'churn', 'promotion', 'department', 'salary')

**Primary Insight**: 24% of the employee have churned and 76% have stayed in the company. This provides a major problem of class imbalances while implementing ML Algorithms.

**Used ML Algorithm**: Decision Trees - Easy to interpret and understand the factors driving the employees to leave the company.

- Performed Hyperparameter Tuning, GridSearch and Cross-validation along with handling the class imbalances found that the best parameters for the model are: Max_depth as 5 and Min. sample in leaf as 50.

- Later Indentified the features impacting Target(Churn) where Satisfaction proves to have most impact on Churn. They are: 'satisfaction', 'evaluation', 'average_montly_hours', 'time_spend_company'.

- Finally used the most important features and performed the same approach as above and evaluated the model. The results are as follows:

   1. Accuracy on the test set: 93.5%
   2. Recall : 92% => Out of all the actual positive instances, the model is able to correctly identify 92% of them as true positives. 
   3. AUC (Area under the ROC Curve) : 93%





