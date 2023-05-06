# Belly Button Biodiversity App with Flask and JavaScript

## Note that I had deleted the app from Heroku since the app deployment was no longer free. However, this repository still has all of the codes and notes for the steps needed to create this dashboard. 

Using Flask, SQLAlchemy, Plotly.js, and Heroku, the objective is to build an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

## Step 1 - Plotly.js

Use Plotly.js to build interactive charts for the dashboard.

* Create a PIE chart that uses data from the samples route (`/samples/<sample>`) to display the top 10 samples.

* Create a Bubble Chart that uses data from the samples route (`/samples/<sample>`) to display each sample.

* Display the sample metadata from the route `/metadata/<sample>`

  * Display each key/value pair from the metadata JSON object on the page

* Update all of the plots any time that a new sample is selected (refresh)

## Step 2 - Heroku
Deploy the Flask app to Heroku.


## App sample:

![biodiversity_dashboard](biodiversity_dashboard.png)
