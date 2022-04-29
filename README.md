# Taxi-Fare-in-New-York
#### This project is about taxi fares in New York
#### There are some training and test data.
#### It has 8 features. {Date-key-pickup Longitude-pickup Latitude-dropoff Longitude-dropoff Latitude-fare amount-passenger-count}
#### &#x1F539;  First we apply some data engineering such as: removing missing data- removing those with negative fare amount or negative passenger count.
#### &#x1F539; Since the number of missing data is less than 5 percent of training data, we can remove those rows in the data frame.
#### &#x1F539; After that, we use a map to see the pickup Longitude-pickup Latitude-dropoff Longitude-dropoff Latitude on the map. we can also remove those data that have a pickup or dropoff coordinate in the water.
#### &#x1F539; at the end we apply some regression algorithms to predict the taxi fare on test data.

