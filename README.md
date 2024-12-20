NYC Taxi Fare Analysis and Prediction

This project explores and analyzes New York City's iconic yellow taxi data to uncover trends and build a predictive model for trip fares. We clean the dataset, visualize temporal and spatial patterns, and evaluate various machine learning models, ultimately achieving the best results with Linear Regression. Key insights include the influence of trip distance, time of day, and passenger count on fares and tips. The repository provides a comprehensive workflow for data-driven insights and predictive modeling.

Highlights:

    Data cleaning and outlier analysis.
    Exploratory data analysis with insightful visualizations.
    Predictive modeling with Linear Regression, Random Forest, Gradient Boosting, and XGBoost.
    Practical business insights for taxi operations.

Keywords: Taxi Data, NYC, Machine Learning, Predictive Modeling, Data Analysis.

Introduction:
New York City is a vibrant metropolis known for its iconic yellow taxis that zip through the bustling streets, catering to millions of rides every day. With their omnipresence and pivotal role in the city’s transportation system, analyzing New York taxi cabs offers a unique opportunity to uncover intriguing patterns and dynamics. We thought it would be fun to dive into this dataset to explore how factors like trip distance, time of day, and passenger behavior influence fares and tips. Beyond just the numbers, this analysis gave us a lens into the city’s rhythm and pulse—one ride at a time. It’s a chance to connect data with the real-world hustle of NYC, uncovering stories hidden in every fare.

Conclusion:


This was a series of analyses and modeling over New York Taxi Cab data in order to find insight from data influencing trip fares and predict the fare_amount using different machine learning models. The following key takeaways are derived after conducting the project.

    Data Exploration and Cleaning

Major cleaning in the dataset with regard to outliers, missing values, and redundant features. Temporal trends were well demarcated for trip demand, average fares, and tipping: High travel times were realized late at night/early morning. Weekdays normally realized high volumes, whereas weekends tended to have high averages in fares and variation in tips.

    Feature Engineering and Correlation Analysis

The most important features of the data were found to be trip_distance, trip_duration, pickup_hour, and passenger_count, all highly correlated with the target variable, fare_amount. Features related to price, such as total_amount, taxes, and surcharges, were excluded to avoid data redundancy.

    Model Selection and Evaluation

The following regression models were tested to forecast fare_amount: Linear Regression outperformed even advanced models such as Random Forest, Gradient Boosting, and XGBoost with the best results on MSE and R². This result is indicative of the relatively linear relationship between independent variables and the target variable.

    Model Performance and Visualization

The actual vs. predicted fare plot showed that most of the fares were well-predicted by the model, while few cases were far away because they were either extreme or outliers. Residual analysis showed that residuals were randomly spread around the horizontal axis, which means no underfitting or overfitting of the data by the model.

    Business Insights

Distance of the Trip: Strongest predictor for the fare amount; the longer the trip, the higher the fare. Time of Day: Fares vary by time of day, with higher rates during late-night hours. Passenger Count: Little effect on fares but may influence tipping behavior indirectly. Vendor Performance: Vendor 2 dominated in terms of trip volume while Vendor 4 seemed to cater to niche or premium rides.

    Recommendations

Taxi companies can further optimize pricing strategies, focusing their efforts on time-based fare adjustments during peak hours. Integration of predictive models like this one will lead to better customer fare estimations, hence more transparency and trust. Vendors will be able to analyze their performance for underperforming time slots to address gaps in service and coverage.

Future Work

Model Improvements:

Explore other features such as weather conditions or holiday flags that could be used to further improve the accuracy of the predictions. Compare the performance of more advanced models by tuning their hyperparameters.

Operational Insights:

Look for outliers, like very large distances or fares, which could indicate anomalies or fraudulent data. Expand Scope: Do similar modeling in other cities or combine ride-hailing data from multiple sources to gain insights that are more general about the industry.

