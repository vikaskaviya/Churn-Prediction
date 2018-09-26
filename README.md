# Churn-Prediction

## Dataset
This is a dataset from a telecom company, of their customers. Based on various features of these customers and their calling plans, we want to predict if a customer is likely to leave the company. This is expensive for the company, as a lost customer means lost monthly revenue!
- Dataset contains 3335 customers information as various features-
> [u'Account Length', u'VMail Message', u'Day Mins', u'Day Calls', u'Day Charge', u'Eve Mins', u'Eve Calls', u'Eve Charge', u'Night Mins', u'Night Calls', u'Night Charge', u'Intl Mins', u'Intl Calls', u'Intl Charge', u'CustServ Calls',u"Int'l Plan", u'VMail Plan']

### company will provide an offer to the customer who are about to churn, thus the prediction model must consider offer cost and revenue for company as a primary factor.  

## Steps
- Reduced the features
- split the data in test and train
- define cost matrix for an offer company what to give a customer
- find out confusion matrix.
- using cost matrix and confusion matrix applied classsifers like Naive bayes and Decision trees
- Compared classifiers using ROC curves, AUC curves and Cost curves
- used different curves for model selection 


## Results
Reduced the average cost per person to  rs.100.95 from rs. 169.23 using ROC,AUC,Cost curves.   
