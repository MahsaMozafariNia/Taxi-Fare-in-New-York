# Taxi-Fare-in-New-York
#### This project is about taxi fare in New York
#### There are some training and test datas.
#### It has 8 features. {Date-key-pickup Longitude-pickup Latitude-dropoff Longitude-dropoff Latitude-fare amount-passenger-count}
#### &#x1F535; First we apply some data engineering such as: removing missing data or a data with negative fare amount of negative passeng-count.
#### {color:blue Since the number of missing data is less than 5 percent of training datas, we can remove those row in the dataframe.}
  #### <font color='blue'> After that we use a map to see the pickup Longitude-pickup Latitude-dropoff Longitude-dropoff Latitude on the map. we can also remove those datas that has pickup or dropoff coordinate in the water.
  #### at the end we apply some regression algorithms to predict fare amount of test data.

