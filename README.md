# Module 10 Challenge
## Topic : Python,sqlAlchemy,Flask,JSON  
### Part1: Analyze and Explore the Climate Data 
  - SurfUp->This folder has climate_start.ipynb file which has the Climate analysis split into 
    - Precipation Analysis by date depicted in bar chart
    - Station Ananlysis to observe the temparatures for recent past 12 months of dataset and illustarated using histogram
  
### Part2:Design Climate App 
  - Surfup-> This folder has app.py file which has the data displayed in browser. Fun using Flask API tool and JSON.
    - '/api/v1.0/precipitation' - Precipation data for past 1 year by date
    - '/api/v1.0/stations' - List of all Stations
    - '/api/v1.0/tobs' : shows the data for Station - USC00519281 for past 1 year in the dataset
    - '/api/v1.0/&lt;start&gt' - is dynamic and requires route as in ex:/api/v1.0/2016-08-23
    - '/api/v1.0/&lt;start&gt;/&lt;end&gt- is dynamic and requires route as in ex:/api/v1.0/2016-08-23/2017-08-23
