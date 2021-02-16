# Project_4


**CHURN PREDICTION WITH SPARK - PYTHON

**PROJECT OVERVIEW**

Music platforms such as youtube, spotify, deezer or another application in general that presents free and premium services for their clients, generally faces the problem of investigating or analyzing the abandonment or desertion rates of their services, either between their own products. or that they took other external services with better conditions. Therefore, it is a common and challenging problem that scientists and data analysts regularly encounter in any customer-facing business. To this end, it seeks to minimize customer churn and churn by detecting in advance which customers are likely to cancel their subscription or resign their services.

This project is about the process of predicting unsubscribing customers using Spark as a tool to design the relevant features, then build machine learning models for the prediction. For this problem I use the Sparkify dataset provided by Udacity, for the realization of this project.


**PROBLEM STATEMENT**

Sparkify (tm) is a web-based music streaming service that requires users to register and log in. This service has two types of subscriptions for users, which are shown below:
Free subscription: In which users listen to music for free, but will also hear ads, such as on YouTube, on deezer, on spotify and other services that offer music.
Paid or premium subscription: Users who pay in this subscription listen to songs without advertising, without interruptions and it allows them to change songs as many times as the user wants.

The subscribed user regardless of their affiliation, at any time can perform any of the following actions:
1. Change from free subscription to paid (premium) .(Upgrade in data)
2. Change from paid subscription (premium) to free. (Downgrade in data)
3. Unsubscribe. (Cancel in data)

Taking into account the above, the objective of this project is to identify users who could potentially cancel their subscription. By identifying this population in advance, we could offer them discounts or other rewards that lead to the user staying with the service for the commercial growth of a company.


**UNDESTANDING THE DATA**

Step by step of how this project was developed 
A. Load and clean the data: the data is loaded and cleaned.
B. Exploratory data analysis: some important features are extracted from the working database.
C. Feature engineering: after familiarizing ourselves with the data and seeing some interesting characteristics, we can select which characteristics of the database would not generate an added value in the construction of the model.
D. Model building and evaluation: models used, random forest and gradient boosting.
E. Metrics: measurements used to choose the best model. Used F1 and confusion matrix.


**CONCLUSION**

Conclusions that were reached after observing the results of the modeling and the development of the aforementioned stages.

**FUTURE IMPROVEMENTS**

Some recommendations are made for future work, since even having an F1 of 89.04%, there is still an important margin to continue improving, perhaps using other models or the same ones and improving the features.


**RESULTS**

In the following link you can find the blog and the results that I shared for the technical public.

https://leo-fajardo-vasquez14.medium.com/are-you-worried-about-customer-churn-4a37978e434f

