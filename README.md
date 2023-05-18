# Predicting RDU Departures

![image](https://user-images.githubusercontent.com/81717153/197347112-4ad1d3e0-5c47-4fca-8430-2e96f14ac547.png)

Flying has always been stressful, and even more so in our post-covid world. These days it seems like flying has gotten worse: more delayed/cancelled flights, more missed connections, more lost luggage, and far worse airline customer service than previously. And flights are more expensive than ever!

I hope to alleviate at least one piece of the puzzle: delays and cancellations. I created a model that predicts whether flights leaving Raleigh-Durham airport in North Carolina will be on time, delayed by less than 1 hour, less than 2 hours, more than 2 hours, or cancelled (a multiclass classification model). 

Hopefully having this tool will ameliorate some of the unavoidable stress of flying! 

# Project Organization

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
