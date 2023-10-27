# Predicting RDU Delays and Cancellations

![image](https://user-images.githubusercontent.com/81717153/197347112-4ad1d3e0-5c47-4fca-8430-2e96f14ac547.png)

## Summary
Flying is an ordeal. You have to wrangle your whole family and your luggage to the airport, where hopefully no one and nothing gets lost; you have to perfectly time your arrival so you have a parking spot and catch the shuttle in time to make your flight; you have to pray that you don't miss your connection and get stuck in a random city overnight. Somehow post-covid, things seem to have gotten exponentially worse (and flights even more expensive).

In this labyrinthine logistical nightmare, flight delays and cancellations are undesireable to say the least. I created a model that predicts whether flights leaving Raleigh-Durham airport in North Carolina will be on time, delayed by less than 1 hour, less than 2 hours, more than 2 hours, or cancelled (a multiclass classification model). I hope that this tool will ameliorate some of the unavoidable stress of flying.

See below: nearly 1/5 flights over this 1-year period were delayed or cancelled.

![image](https://github.com/liyueling13/Predicting-RDU-Delays-and-Cancellations/assets/81717153/da0e1746-a0ba-46e3-99d2-68d3d6f54ac5)


## Data

I downloaded and compiled my data from the DOT Bureau of Transportation Website. To get my dataset to a manageable size, I subsetted data from July 2021—June 2022 (the latest available) and those departing from RDU only. I was left with 52,645 flights and 33 columns (features), some of which were correlated and later discarded during preprocessing.

Here are some plots created during EDA:

![image](https://github.com/liyueling13/Predicting-RDU-Delays-and-Cancellations/assets/81717153/4bd0ad6f-4d0f-475e-a16e-fdd54fc2b82c) ![image](https://github.com/liyueling13/Predicting-RDU-Delays-and-Cancellations/assets/81717153/80f77fec-8d2f-4ccc-9b7b-55e23da94f93)

## Tools and Methodology
