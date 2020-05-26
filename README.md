# Diamonds Quality

## Data Description

This data set contains prices and attributes of 50,0000 diamonds.

## Background

This notebook contains exploratory analysis of the data. Distributions of variables were analyzed in order to understand their relationships with diamond price. Important questions such as which feature affects the price of the diamond the most and vice versa will be discussed.

Regressions were made and measured on certain features in order to have a better understanding of how these features explain the price of a diamond.



![](https://github.com/andrew-alarcon17/Diamonds_Quality/blob/master/Diamond_Visualizations/Faceting.png)

We can say that the color of the diamonds are independent from the diamond depth, but diamond cut is not independent of depth. We also see that the depth of the diamond isn't really related to the price of the diamond. This is also explained thoroughly when we run a regression on depth to explain price.

<img src="https://github.com/andrew-alarcon17/Diamonds_Quality/blob/master/Diamond_Visualizations/Price_Color.png" width="500">

Here we see a clear relationship between price and carat. As the carat of a diamond increases, so does the price.

<img src="https://github.com/andrew-alarcon17/Diamonds_Quality/blob/master/Diamond_Visualizations/Price_Depth.png" width="500">

Here however, depth of a diamond seems much more independent from its price.

## Conclusion

By running all features of a diamond to explain price in an anova linear regression model, we end up getting a high R_sq value. Why is this? This makes sense, considering all of the information we have is closely related to the properties of a diamond, so there is little room to overfit.
