# Insurance-Claims-Model


  The Problem: 
The shift of risk from drivers to insurance companies cannot be taken lightly, and insurance companies should have accurate methods to predict the likelihood of policyholders filing for claims based on their records, geographic location, and the specifics of the vehicle being insured.
It is important for insurance companies to charge higher premium prices to those who bring a higher risk, in order to ensure their survival.
Insurance companies generally operate on profit margins as low as 2%, so it is essential to have a highly accurate model to predict how much will be budgeted for claims.
The slightest inaccuracy can result in detrimental losses to these companies.
The lack of an accurate model to predict claim likelihood poses a problem to companies in the auto insurance industry in terms of charging the appropriate premiums.


   The Dataset: 
The dataset contains ~ 58,000 instances with 44 columns containing information about the driver, region, and vehicle. The last column states whether the  policyholder filed a claim.


  The Solution: 
I have created a model that will leverage data analysis and supervised machine learning to allow insurance companies the ability to charge the appropriate premium price according to the risk associated with the policyholder.
It will leverage several machine learning transformative and predictive algorithms to pre-process the data, as well as analyze trends and common attributes shared amongst vehicles that regularly file for claims, attributes of policyholders, and geographic information.
Our model helps insurance companies to accurately analyze the risk of policyholders, and in turn charge an accurate premium price to offset the risk.

 
  Solution Methods:
Several python libraries were used to pre-process the data, as well as program and visualize the solution (pandas, numpy, seaborn, matplotlib, imblearn and scikit).
Used RandomOverSampler, OneHotEncoder, StandardScaler and ColumnTransformer for data pre-processing.
Tested accuracy of model when using PCA, Ada Boost, Gradient Boost, and XG Boost clustering algorithms to conclude that combining PCA and XG Boost provides the highest accuracy.
The model predicts the likelihood of a claim with 90% accuracy.

