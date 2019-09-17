# Python

# Counterfeit Medicines Sales Prediction

Counterfeit medicines are fake medicines which are either contaminated or contain wrong or no active ingredient. They could have the right active ingredient but at the wrong dose. Counterfeit drugs are illegal and are harmful to health. 10% of the world's medicine is counterfeit and the problem is even worse in developing countries. Up to 30% of medicines in developing countries are counterfeit.

Millions of pills, bottles and sachets of counterfeit and illegal medicines are being traded across the world. The World Health Organization (WHO) is working with International Criminal Police Organization (Interpol) to dislodge the criminal networks raking in billions of dollars from this cynical trade.

Despite all these efforts, counterfeit medicine selling rackets don’t seem to stop popping here and there. It has become a challenge to deploy resources to counter these; without spreading them too thin and eventually rendering them ineffective. Government has decided that they should focus on illegal operations of high net worth first instead of trying to control all of them. In order to do that they have collected data which will help them to predict sales figures given an illegal operation's characteristics.

# Objective
To predict sales figures related to counterfeit medicine selling operations.

# Data Files
Train Dataset = counterfeit_train.csv

Test Dataset = counterfeit_test.csv

# Data Dictionary
Medicine ID: Medicine ID

Counterfeit_Weight: Weight of the counterfeit medicine

DistArea_ID: District ID

Active_Since: Year

Medicine_MRP: Price of the medicine

Medicine_Type: Type of the medicine

SidEffect_Level: Sideffect level(critical,mild)

Availability_rating: Availablity of the counterfeit medicine

Area_Type: Different types of areas

Area_City_Type: Tier 1,Tier 2 and Tier 3

Area_dist_level:DIfferent area district levels like small,medium,high and unknown

Counterfeit_Sales: Sale price of countereit medicine

# Conclusion
I have applied linear,lasso,ridge regression and random forest models.When I compared the performance of the models Random Forest model performed well and achieved mean absolute error of 0.54.




