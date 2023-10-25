# Credit-Risk-Classification

Overview of the Analysis
-------------------------

This challenge was an exercise in using supervised machine learning to analyze financial data, as well as develop predictions based on said analysis. The data utilized in this challenge was a collection of loan data, and included information such as the size of the loan, loan status, the debt-to-income ratio, and total debt owed. This data would be analyzed utilizing a Logistical Regression Model, which was trained on the pre-existing patterns within the data, which was first split into two groups using the train_test_split function. The training portion of the data was run through the LogisticRegression function, to train the model to identify patterns to be used to predict whether a loan was more likely to become healthy or high-risk. Once the model was trained, predications were created using the testing data, which were analyzed for accuracy and precision using both a confusion matrix and a classification report. 


Results
---------------

The results, as depicted by the classification report, are as follows: 

-	Healthy Loans:

    o	The predicted accuracy was listed as 100% of 18,759 entries.
  
    o	The predicted precision was listed as 100% of 18,759 entries.
  
    o	The predicted recall scores were listed as 100% of 18,759 entries.

    
-	High-Risk Loans:

    o The predicted accuracy was listed as 87% of 625 entries.
  
    o	The predicted precision was listed as 89% of 625 entries.
  
    o	The predicted recall scores were listed as 88% of 625 entries.

  
-	Total Accuracy:

    o	For both health and high-risk models combined, the accuracy was 99%.


Summary
-------------

Overall, the Logistic Regression model does appear to predict the data relatively well. It would appear the largest issue this model faces is the uneven spread of data between healthy and high-risk loans. As the performance of the model is directly dependent on the data the model is analyzing, having a more even data set would likely produce a more even set of predictions. The healthy loans would likely have lower accuracy, precision and recall, while the high-risk would have better rates for all three. As it is important to have accurate predictions for both healthy and high-risk loans, it would be advisable for the model to be run against a more evenly split data set prior to being employed. That being said, the model has proven to be quite efficient at predicting loan outcomes, if in need of minor editing. 
