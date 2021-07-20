EDA findings :
- Overall Engagement rate is 14%
- Offer2 had the highest engagement rate among the customers.
- Offer 2 customers owning a 4 door car seem to be the highest in engagement rate
- Customers' engagementrate is higher through "agent" sales channel 19% while call center is the lowest about 11 %
- Customers with Medsized vehicles have the highest engagement rate through agent then web then branch
- Highest engagement interms of income is the (20  to 30 k income bin) through agent
- Total claim amount of engaged customers is slightly higher than the unengaged

Classification Models:

Random forest classification model worked well with 200 trees (estimators) to predict the positive class( Enagement response of 1) about 87% accurate but the recall rate was really low, given the imbalanced data.
Tried different number of estimators using a For loop against the oob error, the best estimator was 400 estimators giving a 99 % accuracy and 96% recall rate.
