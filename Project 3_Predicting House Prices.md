Project 3: Predicting House Prices

Dataset
- Predicting Housing Prices
- dataset from: https://www.kaggle.com/paultimothymooney/zillow-house-price-data/data?select=Sale_Prices_State.csv
- contains housing pricess from January 1996 to March 2020 across all states

Which model
- Predicting the housing sales price by state
- Will use Linear Regression

End-User Interaction
- Graph showing the time series analysis on a website


Project Steps

Train and test model: 
- In jupyter notebook
- *create model for each state (train by itself)
- Facebook prophet: https://facebook.github.io/prophet/docs/quick_start.html#python-api

Save as pkl files: https://github.com/facebook/prophet/issues/725 

Mostly likely won’t need this: [Put into database (postgres or sqllite?)??]

Make graphs/figures (from output put in csv): 
- Aim for Tableau
- Could use Plotly too

Create website with Tableau and/or Flask: 
- Make global variable so it is read in one time so can be used in all flask routes, but only read one time
- To upload flask: 
    - Can load pkl files on flask endpoint
    - Can make dictionary for x and y and values is pkl files

HTML/Bootstrap

Deploy it using Heroku (interactive) or Github Pages (not interactive) 

