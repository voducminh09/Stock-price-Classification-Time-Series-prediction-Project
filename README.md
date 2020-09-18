# Introduction

<img src = "image/Stock1.jpg" width = "620" height = "300">

Every stock market investor knows the pain of stock fluctuation, since predicting the stock market's direction is one of the hardest thing to do. There are many factors involved, from overall economy performance or company's fundamentals to news catalysts or market makers' manipulation. As an investor, I am interested to figure out if Machine Learning algorithms have the potential to unearth patterns in the stock market that human cannot detect, which can be used to improve the accuracy of stock prediction. In this project, I perform stock price prediction by applying Machine Learning algorithms on historical data of Apple and Dow Jones Industrial Average.


## Apple stock price prediction

### Decision Tree
MEA for best max_leaf_nodes: 10.490951367026877
<img src = "image/Apple Decision Tree.PNG" width = "600" height = "360">

### Random Forest
MAE for Random Forest Model: 10.508806363636364
<img src = "image/Apple Random Forest.png" width = "600" height = "360">

### k-nearest Neighbor
MAE for k-nearest Neighbor Model: 42.37149350649351
<img src = "image/Apple K-nearest neighbor.png" width = "600" height = "360">

### Prophet
MAE for Prophet Neighbor Model
<img src = "image/Apple Prophet.png" width = "600" height = "360">

### ARIMA
MAE for ARIMA Model: 11.078197046913763
<img src = "image/Apple ARIMA.png" width = "600" height = "360">

## Dow Jones index price prediction

### Decision Tree
MEA for best max_leaf_nodes:212.06950820547277
<img src = "image/Dow Decision Tree.png" width = "600" height = "360">

### Random Forest
MAE for Random Forest Model: 189.0973996753243
<img src = "image/Dow Random Forest.png" width = "600" height = "360">

### k-nearest Neighbor
MAE for k-nearest Neighbor Model: 1203.5057244155848
<img src = "image/Dow K-nearest neighbor.png" width = "600" height = "360">

### Prophet
MAE for Prophet Neighbor Model: 4222.767106506855
<img src = "image/Dow Prophet.png" width = "600" height = "360">

### ARIMA
MAE for ARIMA Model: 3258.3506585789373
<img src = "image/Dow ARIMA.png" width = "600" height = "360">
