## Project description
You work for the OilyGiant mining company. Your task is to find the best place for a new well.

Steps to choose the location:
- Collect the oil well parameters in the selected region: oil quality and volume of reserves;
- Build a model for predicting the volume of reserves in the new wells;
- Pick the oil wells with the highest estimated values;
- Pick the region with the highest total profit for the selected oil wells.

You have data on oil samples from three regions. Parameters of each oil well in the region are already known. Build a model that will help to pick the region with the highest profit margin. Analyze potential profit and risks using the Bootstrapping technique.

Project Instructions:

Step 1. Download and prepare the data. Explain the procedure.

Step 2. Train and test the model for each region:
- Split the data into a training set and validation set at a ratio of 75:25.
- Train the model and make predictions for the validation set.
- Save the predictions and correct answers for the validation set.
- Print the average volume of predicted reserves and model RMSE.
- Analyze the results.

Step 3. Prepare for profit calculation:
- Store all key values for calculations in separate variables.
- Calculate the volume of reserves sufficient for developing a new well without losses. Compare the obtained value with the average volume of reserves in each region.
- Provide the findings about the preparation for profit calculation step.

Step 4. Write a function to calculate profit from a set of selected oil wells and model predictions:
- Pick the wells with the highest values of predictions.
- Summarize the target volume of reserves in accordance with these predictions
- Provide findings: suggest a region for oil wells' development and justify the choice. Calculate the profit for the obtained volume of reserves.

Step 5. Calculate risks and profit for each region:
- Use the bootstrapping technique with 1000 samples to find the distribution of profit.
- Find average profit, 95% confidence interval and risk of losses. Loss is negative profit, calculate it as a probability and then express as a percentage.
- Provide findings: suggest a region for development of oil wells and justify the choice.
