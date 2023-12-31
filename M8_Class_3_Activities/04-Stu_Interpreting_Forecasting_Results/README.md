# Assessing Market Opportunities for Alpaca Wool Scarves: Interpreting the Forecasting Results

In this activity, you’ll interpret the time series forecasting results derived from Google Trends data, which reflects the market demand in Canada and Uruguay for alpaca wool scarves. The purpose will be to validate market opportunities to help the Aymara indigenous people in Bolivia export alpaca wool scarves to different countries or regions.

You’ll continue collaborating with the International Cooperative Alliance and you’ll use Prophet to validate the prospective market opportunities.

## Instructions

1. Open [Google Colab](https://colab.research.google.com/), and then import the provided notebook.

2. Run the initial code to set up the notebook, prepare the data, and use Prophet for time series forecasting.

3. Plot the Prophet predictions by using the `plot` function. Pass the forecasts for Canada and then Uruguay as the parameters.

4. Analyze the forecast results by using the pandas `plot` function to plot the “yhat,” “yhat_lower,” and “yhat_upper” columns in the forecast DataFrame for the Canada and Uruguay models. Before creating these plots, set the “ds” column as the DataFrame index.

5. Use the `plot_component` function on the Prophet models to analyze the patterns of the Google Trends time series data for the Canada and Uruguay models. Before creating these plots, be sure to reset the index by converting “ds” back to a column.

---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
