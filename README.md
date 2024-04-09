# DSC530-Topic-2-Part-2-Time-Series-Feature-Engineering
 An assignment for DSC530 at GCU that focused on feature engineering for time-series data.

 Check out the full report [here.](https://github.com/jhould007/DSC530-Topic-2-Part-2-Time-Series-Feature-Engineering/blob/main/Part%202%20Time%20Series%20Feature%20Engineering.ipynb)

# Assignment Instructions
Feature engineering is the process of adjusting the representation of the data to improve the efficacy of the model. In time series, data scientists construct the output of their model by identifying the variable that they need to predict at a future time (ex: future energy demand or load next month) and then leverage historical data and feature engineering to create input variables that will be used to make predictions for that future date.

For this activity, in 500-750 words, answer the following:
1. Discuss the main goals/benefits of performing feature engineering on Time-Series data.
2. Perform the following types of Features on your selected time-series dataset and report the results of each:
- Date Time Features: from the Date column, "Feature Extract" three additional columns to your data frame: one for the Year, one for the Month, and one for the Day. Show the results.
- Lag Features: use the shift function to "Feature Extract" three additional columns: same day last week, same day last month, same day last year. Show the results.
- Window Features: Use the rolling method to "Feature Extract" an additional column that shows a 2-month rolling average. Show the results.
- Expanding Feature: here, we're not considering window size. We want to consider all the values in the data frame. Use the expanding method to "Feature Extract" an additional column that shows the maximum value till date. Show the results of the data frame.
3. Discuss some additional insights you gained from leveraging the additional knowledge you performed in the previous step. How can this help you build a better time series forecasting solution as a data scientist?
4. "Feature Extract" an additional column called "Q" to show the quarterly data of your data frame by using the resample function. Show the results. Hint: call the mean of the resample function.
5. Perform the same step you did in step 4, but show the Yearly data in this step.

APA style is not required, but solid academic writing is expected. This assignment uses a rubric. Please review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion. You are not required to submit this assignment to LopesWrite.
