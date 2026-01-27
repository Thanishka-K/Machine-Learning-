# Day 1: Linear Regression
What it is: Linear Regression is used to predict a continuous numerical value.
It assumes there is a direct, straight-line relationship between your input (Independent Variable) and your output (Dependent Variable).
  
In simple terms, it tries to draw the "best fit" line through a bunch of data points so that the distance between the line and the actual points is as small as possible.
## The Core Formula: 
Similar to the equation for a line: y=mx+c. In ML y=wX+b, 
  * where y: The prediction (Target)
  * X:The input (feature)
  * w:The weight (how much X affects y)
  * b:The bias (the starting point/intercept)

## Real-World Example: Predicting House Prices
Imagine being a real estate agent trying to estimate how much a house will sell for based on its size.
* The Data: You have data on 50 houses. You plot "Square Footage" on the x-axis and "Price" on the y-axis.The Trend: Generally, as square footage goes up, the price goes up.
* The Model: Linear Regression draws a line through those points.
* The Prediction: If a new house comes on the market that is 2,000 sq. ft., you find 2,000 on the x-axis, move up to your line, and see where it hits the price on the y-axis.
  
