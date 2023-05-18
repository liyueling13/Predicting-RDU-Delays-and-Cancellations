# Predicting RDU Departures

![image](https://user-images.githubusercontent.com/81717153/197347112-4ad1d3e0-5c47-4fca-8430-2e96f14ac547.png)

Flying has always been stressful, and even more so in our post-covid world. These days it seems like flying has gotten worse: more delayed/cancelled flights, more missed connections, more lost luggage, and far worse airline customer service than previously. And flights are more expensive than ever!

I hope to alleviate at least one piece of the puzzle: delays and cancellations. I created a model that predicts whether flights leaving Raleigh-Durham airport in North Carolina will be on time, delayed by less than 1 hour, less than 2 hours, more than 2 hours, or cancelled (a multiclass classification model). 

Hopefully having this tool will ameliorate some of the unavoidable stress of flying! 

# Project Organization

├── LICENSE

├── README.md          <- The top-level README for developers using this project.

│

├── Data

│   ├── Raw Data - OST Flights Info        <- The original data downloaded from the DOT Bureau of Transportation Website
│       └── Jul_2021.csv

        └── Aug_2021.csv
        
        └── Sept_2021.csv
        
        └── Oct_2021.csv
        
        └── Nov_2021.csv
        
        └── Dec_2021.csv
        
        └── Jan_2022.csv
        
        └── Feb_2022.csv
        
        └── Mar_2022.csv
        
        └── Apr_2022.csv
        
        └── May_2022.csv
        
        └── Jun_2022.csv
        
│   ├── Interim        
│       └── RDU_departures.csv
│   └── Final            <- The final data used for modeling
│       └── X_train2.csv
        └── X_test2.csv
        └── y_train2.csv
        └── y_test2.csv       
│
├── Jupyter Notebooks
│   ├── Capstone 2 - Data Wrangling - RDU Departures.ipynb
│   ├── Capstone 2 - Exploratory Data Analysis - RDU Departures.ipynb
│   ├── Capstone 2 - Preprocessing - RDU Departures.ipynb
│   └── Capstone 2 - Modeling - RDU Departures.ipynb 
│
├── Reports
│   ├── Capstone 2 - Final Report - RDU Departures.pdf
│   └── Model Metrics.txt 
