# SYRIATEL CUSTOMER CHURN PREDICTION AND RETENTION STRATEGY

A deep analysis of SyriaTel was conducted to address a severe business issue the decrease of revenue loss due to to the identification of customers who are most likely to churn (leave the service). The research narrowed down on the major causes of customer exits by using Target Recall as the main form of measure to make sure that the greatest number of at risk customers are retrieved before they exit

## Business Understanding

The project will address the customer retention issue that must be informed to make data driven etention decisions by the Head of the Customer Success Division. The audience needs practical non technical insights obtained from the data analysis.

### Stakeholder and Key business questions

*** Stakeholder:** The telcom business itself, whose objective is to mitigate revenue loss and enhance customer loyalty through proactive outreach.

*** Key business questions:**
1. To find out what usage patterns pose the greatest risk, what is the relationship between churn and variables such as Total Day Minutes and Customer service calls?
2. Regarding the performance of the model, which model(Logistic Regression vs Decision Tree) gives the best recall so that we do not leave out as many at risk customers?
3. What effect must risk mitigation methods such as special discounts or special audits have on customer characteristcs such as Voice mail or International Plans?

## Data understanding and analysis

Project presentation: Stakehoders can examine churn drivers, usage frequency and model performance through the comprehensive project presentation
*** Presentation slides link{}** 
#### Source and description of data
The data used is the SyriaTel Customer Churn dataset, supplying documentation of 3,333 customer accounts and 21 variables.
#### Data preparation
1. In the target variable(churn), the type of variables was changed to integers
2. Multi-column redundancies on the charge (which were values that were correlated with minutes) were removed.
3. One-Hot Encoding was used to convert categorical variables such as International Pland and Voice Mail Plan.
4. StandardScaler was utilised to normalize numerical features so that the baseline model was fair in treating all the metrics of usage.

## Three Visualizations
The key conclusions that went into creating the final business suggestions are depicted in the following:
1. *** Baseline Confusion Matrix:** Visualizes the 86% "Accuracy trap" the model correctly depicts those who stay(550) and misses most those who leave (74 missed)
2. *** Logistic Regression Coefficients:** Shows the mathematical cause of churn and how much probability of leaving to raise with an additional service call.
3. *** Decision Tree Features Importance:** Ranking the most important factors that are considered as branching, it has been found to identify the thresholds of usage, which would best classify loyal customers and churns.

## Conclusion
The association between customer behavior and probability of churning was assessed appropriately. According to the results, even though a baseline model might seem correct, it is blind to customers that matter most (the churners). Decision Tree model was the best business tool as the number of unwarned departures was significantly decreased.

### Three Relevant Findings
1. ***Finding 1** - Service Interaction Risk: Customer Service Calls is the best predictor of churn. As soon as a customer has made a certain number of interactions, the churning probability grows exponentially, which indicates that these calls are literally the cries of help that cannot be worked out.

2. *** Finding 2**- High Usage Risk: Customers having high Total Day Minutes have a higher probabilistic number of churning. This is an indication that the highly used customers of SyriaTel might be getting better high rate services with competitors.

3. *** Finding 3** - Model Optimization: Replacing a Logistic Regression with a Decision Tree the Target Recall increased to 0.24 to 0.65. This implies that the business is currently able to recognize and perhaps save 65% of churners, as opposed to 24% with the base strategy.

