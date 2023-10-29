# Power-Consumption-Prediction-ML-Kaggle-Hackathon-by-Blend360
**Description**

You have been hired as a Data science consultant by the Electricity board of Hyderabad to predict power consumption across three zones across the city. Your forecasts will help the electricity board to plan for the projected electricity requirements and make necessary agreements to avoid at shortfall of power to the city. You’ll develop models trained on historical power consumption data across the three zones. Besides the power consumption data, you will also have some other parameters that can impact the power consumption in a region. With reasonable efforts, you should be able to get to a MAPE performance of less than 6%.

**Evaluation**

Submissions are evaluated on MAPE (Mean Absolute Percentage Error) between predicted and actual values. Final evaluation metric is the mean of the MAPEs calculated for three zones. Submission Format: For each DateTime you must predict the power consumption for all 3 zones. The file should contain a header and have the following format: DateTime, Zone 1 Power Consumption, Zone 2 Power Consumption, Zone 3 Power Consumption 2017-12-01 00:00:00,37237.94,28259.26,38923.04 2017-12-01 00:10:00,16652.03,26271.69,22312.31 2017-12-01 00:20:00,31705.53,30985.58,23373.82 2017-12-01 00:30:00,46446.41,23514.69,6275.89 etc.

**Citation**

0812, udheep, vaibhaw khemka. (2023). Hyderabad City Power Consumptions. Kaggle. https://kaggle.com/competitions/hyderabad-city-power-consumptions

**Dataset Description**

**Training Data:** You’re provided with 11 months (Jan17-Nov17) of power consumption data of each of the three zones at a granularity of 10 minutes interval. In addition to power consumption data, you’re also provided with Temperature, Humidity, Wind Speed, general diffuse flows, diffuse flows. Ignore the units of all the variables provided.

**Testing Data:** You’re supposed to use the developed models/solution to predict power consumptions in each of the three zones for the same granularity of 10 minutes for a period of 1 month (Dec17).

**Files**

Hyderabad_Power_Train.csv - the training set
Hyderabad_Power_Test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
Columns
example_id - definition of example_id
feature_1 - definition of feature_1
etc.
