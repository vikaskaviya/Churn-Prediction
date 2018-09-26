# Churn-Prediction

## Dataset
This is a dataset from a telecom company, of their customers. Based on various features of these customers and their calling plans, we want to predict if a customer is likely to leave the company. This is expensive for the company, as a lost customer means lost monthly revenue!
- Dataset contains 3335 customers information as various features-
> [u'Account Length', u'VMail Message', u'Day Mins', u'Day Calls', u'Day Charge', u'Eve Mins', u'Eve Calls', u'Eve Charge', u'Night Mins', u'Night Calls', u'Night Charge', u'Intl Mins', u'Intl Calls', u'Intl Charge', u'CustServ Calls',u"Int'l Plan", u'VMail Plan']

### company will provide an offer to the customer who are about to churn, thus the prediction model must consider offer cost and revenue for company as a primary factor.  

## Process
- Reduced the features
- split the data in test and train
- define cost matrix for an offer company what to give a customer
- find out confusion matrix.
- using cost matrix and confusion matrix applied classsifers like Naive bayes and Decision trees
- Compared classifiers using ###ROC curves, AUC curves and Cost curves



Telecom company was losing its customers provided its users' dataset. I applied various ML algorithms, ROC curve and confusion matrix to identify users who will churn and what minimum offer to give them so they don't churn and company stays in profit.
