# Credit-Score-Classification-Model
Credit Score Classification Model using SAS Enterprise Miner<br />

In this project, we aim to predict the credit score of customers by leveraging their credit-related information, thus enabling finance companies to evaluate the customer’s credit risk level. The analysis will be performed and visualized based on data mining steps developed by SAS institute named SEMMA, which follows with the process sequence of Sample, Explore, Modify, Model and Assess.
Therefore, the objectives of this project are:<br />
1. To explore the key factors that have significant impact on an individual’s credit score.<br />
2. To build a credit score classification model.<br />
3. To assess various models and determine the best model in classifying customers’ credit score.<br />

Overview <br />
In the data exploration stage, there are variables of several error types that required data preprocessing and cleaning. They are then modified using different methods such as imputation and transformation.<br />
In the Modelling and Assessment Stage, several models are selected to classify the credit score of the customers based on their credit-related information (features) and these models are assessed based on various evaluation metrics.<br />
The following key findings were discovered during the data exploration phase by examining the relationships between features and target, as well as significant patterns within the modified data. These valuable insights highlight the factors that are closely associated with credit scores, thus allowing us to successfully achieve one of our project goals, which is to identify the key determinants of creditworthiness.<br />
1. The most frequent payment behavior of the borrowers is low spending with small value payments and most of them are scientists.<br />
2. Based on the relationship between the input variables, it shows that annual income and monthly in hand salary both have high positive correlation, followed by loan and total EMI per month. Both relationships are logical as annual income and monthly in hand salary are related to the borrower’s income earned. When the loan amount is high, eventually total EMI to repay is high, given that the downpayment is constant. Meanwhile, the interest rate and credit history age have a negative correlation value, indicating that interest rate is lower when the credit history age is higher. This is due to lenders being able to track a lengthier pattern of good credit history of a borrower.<br />
3. From an association standpoint between input variables and target variable using Chi-Square plot, credit mix and payment of minimum amount variables show higher correlation with credit score, which potentially shows greater variable importance in classifying the credit score. <br />

By incorporating these findings into model development, we can ensure that the resulting model captures the important features that contribute to creditworthiness and provides more precise predictions on customers’ credit scores. <br />
The interesting findings in modelling and assessing phase are described below. <br />

4. From the decision tree model, variables with the highest important values are interest rate, credit mix and the month. These variables demonstrate a stronger influence on the model’s prediction compared to others. However, it should not be treated as a general statement about the variable importance in the real world.<br />
5. In the decision tree model, the interest rate is selected as the root node as it has the highest level of information gain. In terms of splitting, total EMI per month has the highest splitting number, which indicates that the tree considers total EMI per month most informative and has highest discriminatory power for making splits in the data.<br />

In this study, we have developed the credit score classification model based on customers’ credit related information and assessed the best classification model by evaluating performance of different models on various metrices. Based on the result, we are able to justify that Gradient Boosting is the best credit score classification model as it provides the best accuracy with the lowest misclassification rate. All objectives of this study are successfully accomplished, including determining the key factors affecting the credit score, building credit classification model and assessing the best models.
