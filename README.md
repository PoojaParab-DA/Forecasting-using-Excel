# Forecasting using Excel

Scenerio: An Excel sheet tracks the daily views of a YouTube channel from June 1, 2022, to January 14, 2023. My task is to forecast the views for the next seven days, up to January 21, 2023.

## Methods Used
- Using Function
- Using Graph
- Using Forecast sheet

### Using Function

=FORECAST(x, known ys, known xs)

### Using Graph

I created a graph with days on the x-axis and views on the y-axis. To analyze the data, I applied a polynomial trendline of order 3, maximizing the R² (R-squared) value. Using the forecast feature, I projected the views for the next seven days.

With observation we can see the values are increasing with date. 

![image](https://github.com/user-attachments/assets/57b84196-68d8-4fc2-a722-66cd96b2e906)

![image](https://github.com/user-attachments/assets/3d987578-8090-48c2-a819-e0e55afabd91)

### Using Forecast sheet

select complete data(including heading rows) > data > forecast > forecast sheet

![image](https://github.com/user-attachments/assets/c4855a83-90b4-45bb-8cf3-7f31577f92a6)


Changes can be done as per our requirement. 

### The actual and forecasted values

![image](https://github.com/user-attachments/assets/80a949ff-79cb-4af3-9731-e61e00988fd1)

Conclusion: In excel, forecasting can be done using formula, graphs and forecast sheet. Excel allows us to predict both future and past values using the Forecast Sheet, which is an effective tool for generating predictions. It also provides lower and upper confidence bounds to help assess the reliability of the forecasts. The comparison between the actual values and the forecasted values reveals notable similarities.
