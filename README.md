PRCP-1025-FlightPricePrediction

Problem Statement
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain. 

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model which will help the customers to predict future flight prices and plan their journey accordingly.

Dataset Link:
We have to analyze the flight fare prediction using Machine Learning dataset using essential exploratory data analysis techniques then will draw some predictions about the price of the flight based on some features such as what type of airline it is, what is the arrival time, what is the departure time, what is the duration of the flight, source, destination and more
Link : https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/flight-fare.zip

Attribute Information : 

1.	Airline: So this column will have all the types of airlines like Indigo, Jet Airways, Air India, and many more.
2.	Date_of_Journey: This column will let us know about the date on which the passenger’s journey will start.
3.	Source: This column holds the name of the place from where the passenger’s journey will start.
4.	Destination: This column holds the name of the place to where passengers wanted to travel.
5.	Route: Here we can know about what the route is through which passengers have opted to travel from his/her source to their destination.
6.	Arrival_Time: Arrival time is when the passenger will reach his/her destination.
7.	Duration: Duration is the whole period that a flight will take to complete its journey from source to destination.
8.	Total_Stops: This will let us know in how many places flights will stop there for the flight in the whole journey.
9.	Additional_Info: In this column, we will get information about food, kind of food, and other amenities.
10.	Price: Price of the flight for a complete journey including all the expenses before onboarding.
Model Comparison Report

Create a report stating the performance of multiple models on this data and suggest the best model for production.

Report on Challenges faced

Create a report which should include challenges you faced on data and what technique used with proper reason.


Note:-All above tasks have been created on a single jupyter notebook and share the same while final submission of project.
Objective:
To predict the flight prices using machine learning models, allowing customers to forecast flight fares and optimize booking strategies.

Model Performance:
Before Hyperparameter Tuning:

XGBoost Regressor: R² = 0.94 (Top performer)
Random Forest Regressor: R² = 0.93
Decision Tree Regressor: R² = 0.88
After Hyperparameter Tuning:

Random Forest Regressor: R² = 0.93 (Top performer)
XGBoost Regressor: R² = 0.91
Gradient Boosting Regressor: R² = 0.91
Key Insights:
XGBoost was the most effective model before tuning, with an R² of 0.94, meaning it explained 94% of the variability in flight prices.
After tuning, Random Forest emerged as the best model, showing that hyperparameter adjustments significantly improved its performance.
Gradient Boosting was a strong performer, maintaining an R² of 0.91, indicating a consistent and reliable predictive model.
Conclusion:
The model can be used by airlines, customers, or travel platforms to forecast ticket prices, enabling customers to make informed booking decisions. By leveraging the insights from different model performances, airlines can optimize their dynamic pricing strategies.

