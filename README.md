# Predicting_generous_tipper
Use random forest and XGBoost models to predict whether or not a customer is a generous tipper.
## Overview
The goal of  this  project  was  to  analyze  the  data  collected  by  the TLC  and  to  build  a random forest machine learning model and XGBoost model to predict if a customer will not leave a tip. 
After the data team built the identified models and performed the testing，random forest architecture yielded slightly better predictions.The model’s F1 score was 0.7235.
Based on the model, a trip’s itinerary, predicted fare amount, and time of day may have a strong enough relationship with tip amount that we could accurately predict generous tipping.
It is clear that these factors do indeed help predict tipping.
## Business Understanding
The TLC wants to use the model in an app that will alert taxi drivers to customers who are unlikely to tip, since drivers depend on tips.If we can predict Whether or not a customer is a generous tipper, it might be able to find ways to generate more revenue for taxi cab drivers.Due to ethical concerns, the modeling objective shifted to predict "generous" tippers (≥ 20%) to balance drivers' and passengers' interests.
## Data Understanding
There are two dataframes: one containing the original data, the other containing the mean durations, mean distances, and predicted faresThe features included information on trip duration and destination, vendor used, toll information, and payment type. Join the two dataframes，We can get the data consisting of approximately 22699 rows and 21 features. The bar chart right shows how many generous tippers (>=20%) versus tippers(=<20%） that exist in the data set.
## Modeling and Evaluation
The data team used two different modeling architectures（random forest and XGBoost) and compared their results. Both models performed acceptably, with a random forest architecture yielding slightly better predictions.The model’s F1 score was 0.7235.The right plot shows F1 scores  for random forest and XGBoost model.
## Conclusion
The resulting algorithm is usable to predict riders who might be generous tippers, with reasonably strong precision, recall, F1, and overall accuracy scores.
As a next step, the data team can consult the TLC to share the model results and recommend that the model could be used as an indicator of tip amount. However, additional data would be needed to realize significant improvement to the model.





