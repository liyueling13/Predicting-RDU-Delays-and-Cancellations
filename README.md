# Predicting RDU Delays and Cancellations

![image](https://user-images.githubusercontent.com/81717153/197347112-4ad1d3e0-5c47-4fca-8430-2e96f14ac547.png)

## Summary
Flying is an ordeal. You have to wrangle your whole family and your luggage to the airport, where hopefully no one and nothing gets lost; you have to perfectly time your arrival so you have a parking spot and catch the shuttle in time to make your flight; you have to pray that you don't miss your connection and get stuck in a random city overnight. Somehow post-covid, things seem to have gotten exponentially worse (and flights even more expensive).

In this labyrinthine logistical nightmare, flight delays and cancellations are undesireable to say the least. I created a model that predicts whether flights leaving Raleigh-Durham airport in North Carolina will be on time, delayed by less than 1 hour, less than 2 hours, more than 2 hours, or cancelled (a multiclass classification model). I hope that this tool will ameliorate some of the unavoidable stress of flying.

![image](https://github.com/liyueling13/Predicting-RDU-Delays-and-Cancellations/assets/81717153/6a51d029-9588-44fc-8905-f8e1a0538d4c)


## Data

I downloaded and compiled my data from the DOT Bureau of Transportation Website. In order to 

├── LICENSE<br/>
├── README.md <- The top-level README for developers using this project.<br/>
├── Data<br/>
&nbsp; &nbsp; &nbsp; &nbsp; ├── Raw Data  <- The original data downloaded from the DOT Bureau of Transportation Website<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Jul_2021.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Aug_2021.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Sept_2021.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Oct_2021.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Nov_2021.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Dec_2021.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Jan_2022.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Feb_2022.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Mar_2022.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Apr_2022.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── May_2022.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── Jun_2022.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; ├── Interim<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── RDU_departures.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; └── Final <- The final data used for modeling<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── X_train.csv  <- This was too large to upload but can be generated using the Preprocessing NB<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── X_test.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── y_train.csv<br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;   └── y_test.csv<br/>
├── Jupyter Notebooks<br/>
&nbsp; &nbsp; &nbsp; &nbsp; ├── Capstone 2 - Data Wrangling - RDU Departures.ipynb<br/>
&nbsp; &nbsp; &nbsp; &nbsp; ├── Capstone 2 - Exploratory Data Analysis - RDU Departures.ipynb<br/>
&nbsp; &nbsp; &nbsp; &nbsp; ├── Capstone 2 - Preprocessing - RDU Departures.ipynb<br/>
&nbsp; &nbsp; &nbsp; &nbsp; └── Capstone 2 - Modeling - RDU Departures.ipynb<br/>
├── Reports<br/>
&nbsp; &nbsp; &nbsp; &nbsp; ├── Capstone 2 - Final Report - RDU Departures.pdf<br/>
&nbsp; &nbsp; &nbsp; &nbsp; └── Model Metrics.txt<br/>
