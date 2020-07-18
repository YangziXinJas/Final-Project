# Final-Project

Helpful example of process: 
 https://www.kaggle.com/niyamatalmass/machine-learning-for-time-series-analysis/notebook?select=City_time_series.csv#-We-see-that-the-data-set-has-the-housing-price-from-1996-to-2017.-We-can-use-this-data-to-predict-the-price-of-2018-and-next-years.--


Train and test model
  - In jupyter notebook
  - *create model for each state (train by itself)
  - Facebook prophet
  - https://facebook.github.io/prophet/docs/quick_start.html#python-api

Save as pkl files
  - https://github.com/facebook/prophet/issues/725 
  
Mostly likely won’t need this: [Put into database (postgres or sqllite?)??]
Make graphs/figures (from output put in csv)
  -Aim for Tableau
  -Could use Plotly too

Create website: Tableau and/or Flask
  - Make global variable so it is read in one time
      - So can be used in all flask routes, but only read one time
  - To upload flask
      - Can load pkl files on flask endpoint
      - Can make dictionary for x and y and values is pkl files
      
HTML/Bootstrap

Deploy it using Heroku (interactive) or Github Pages (not interactive) 

     




