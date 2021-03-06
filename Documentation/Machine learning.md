**Feature Engineering:**

1) Chi Square test-
The Chi-Square test is best defined as a statistical hypothesis test. This test is used either for comparing a group having a value or in comparing multiple groups with categorical data. The advantages of this test are the robustness with respect to the given data. 
It can only be used when two categorical variables are there and related to some population. The Chi-square test is a goodness fit statistic because it measures how well the observation data fits the distributed data.
 
2) Z-score: 
A Z-score is a hypothesis test. The samples are normally distributed while the test is being performed. It's only utilized when the standard deviation is known, and the sample size is always large.
In other words, it verifies the sample's hypotheses about the same population.



**Correlation Matrix:**

![image](https://user-images.githubusercontent.com/71124557/168903047-2a542c1a-646e-4c0e-91bf-5765402cd125.png)



**Machine Learning Models Used:**

1) Logistic Regression

2) Logistic Regression using Grid Search Cross Validation at various regularization strengths and liblinear solver

3) Logistic Regression using Grid Search Cross Validation at various regularization strengths and saga solver

4) Decision Tree Classifier

5) Decision Tree with Grid Search CV

6) Support Vector Machine

7) K-Nearest Neighbours

8) Adaboost Model

**Conclusions:**

1) The classifier's efficiency to identify the model is determined by the Area Under the Curve (AUC) Score.

2) Initial AUC score using logistic regression model is 58 percent, that implies that the model is 58 % efficient in determining the target classes.

3) Using Logistic Regression with Grid Search Cross Validation & Liblinear Solver, the AUC value is still 58%.

4) By applying Logistic Regression with Grid Search CV & Saga Solver is also having the same AUC value, which  is 58%.

5) Upon applying Decision trees classification model, the score has improved to 80%.

6) Then again, we executed Decision tree with grid search cross validation which gave a score of 88%.

7) With the Adaboost model, we got ROC_AUC score of 52%, which is way less comparing to decision tree and logistic regression models.

8) After implementing Adaboost model, we implemented Support vector model which gave a score of 74%..

9) Lastly, we used K- Nearest Neighbors model that enhanced the ROC_AUC score around 84%.

10) On concluding, decision tree classifier has the highest score. Thus, we use this model for further deployment when implanting with live application.

**Results:**

| Model      | AUC Score |
| :---        |    :----:   |
| Logistic regression      | 58% | 
| Logistic regression with Grid seach CV and Liblinear solver    | 58% | 
| Logistic regression with Grid seach CV and Saga solver     | 58% | 
| Decision Tree   | 80% | 
|  Decision Tree using Grid search CV    | 88% | 
| Adaboost model | 52% | 
| Support vector machine     | 74% | 
| K- Nearest neighbor | 84%    |
