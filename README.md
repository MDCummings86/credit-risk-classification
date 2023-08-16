# credit-risk-classification
<ins>Overview</ins>

For this assignment, I aimed to create a logistical regression model to aid in identifying healthy and high risk loans for a lending client. This is important because lenders need to understand what factors lead to healthy and high-risk performance of their various loan products in order to optimize profits and customer satisfaction. Analyzing and utilizing model data on the creditworthiness of borrowers by using historical lending activity from a peer-to-peer lending services company can help prevent financial hardships for customers and unnecessary work for employees.

<ins>Description of Accuracy, Precision, and Recall Scores of the Model</ins>

* Accuracy - The balanced accuracy score for the model is 99.4% which is very strong and is an expected increase from the 95.2% from the log_predictions.

* Precision - 100% of the model's predictions about healthly loans are correct, while the precision for high-risk loans is 84%. 

* Recall - For both the healthly and high-risk loans, 99% of the positive cases were caught. 100% of the positive predictions were correct for the healthy loans while only 91% of the positive predictions were correct for the high-risk loans.

<ins>Summary</ins>

The logistic regression model fits nicely with the oversampled data. We can see the accuracy of the model is now higher at 99% for the macro average of the recall. This is an improvement from the original predictions. I would confidently recommend utilization of this model by the company for the following reasons:

The precision of the model with regards to the healthy loans is high at 100%, so there would be minimal risk of missclassification in the prediction. If a healthly loan is missclassified as a high-risk loan, the bank may spend more money maintaining the product than it needs too with respect to additional underwriting and review requirements. 

The precision of the model with regards to the high-risk loan labels is still high at 84%. A lower precision is to be expected with much less data as the output. A high recall still supports a favorable confusion matrix breakdown. If a high-risk loan is mistakely identified as a healthy loan, then the bank could eat costs due to default of the loan, additional servicing costs and loss mitigation. Of course, the potential for customer/client loss is also high with a model that fails to predict the factors leading to a high-risk loan product. 


