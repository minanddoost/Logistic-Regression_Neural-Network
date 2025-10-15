# Logistic Regression and Neural Network
Logistic Regression &amp; Neural Network - Quality check 

Problem: Unable to detect when product quality incident occurs. 

Solution: Use machine learning logistic regression with multiple inputs to predict a quality issue

Hypothesis: Find that individual properties on their own will not be enough to confidently predict a product quality incident
Purpose: Select threshold value to correctly identify product quality issue, but not too low that false positives become frequent
	
Data Set proccessing steps:

Manipulate data set using pandas/numpy i.e. fill in missing data points

Scrub instrumentation for periods of maintenance, sample data when unit outage

Make sample point from text to numeric (i.e. <1 to 1)

Significant figures rounding

Add charge rate rate of change column

Show key parameters that had largest impact on graph using matplot

2015-2016 missing filter dp and sample analysis

Split using testing and training to check accuracy of model prediction i.e. use 80% training and 20% testing

	Use ROC curve to help choose optimum threshold values for key parameters
  
	ROC = Receiver Operator Curve i.e. graph true positive rate versus false positive rate
