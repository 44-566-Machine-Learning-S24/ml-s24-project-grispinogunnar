# README.md
## Contents:
* [Raw Data](#raw-data)
* [Data](#data)
* [Analysis](#analysis)
* [Conclusions](#conclusions)
### Raw Data
Source: Data was the 2015 World Happiness Report, pulled from the Sustainable Development Solutions Network <br>
CSV: [World Happiness Report](#2015.csv)<br>
Data Setup: [initial_data_setup](#initial_data_setup.ipynb)<br>
### Data
Transformations: Applied a mapping function to give region a numerical value.<br>
Visualizations: Various plots and graphs are included to show our data, per section.<br>
### Analysis
Metrics: Metrics for our different models are included in each section.<br>
Models:
* [Linear](#linear)
* [Decision Trees](#classification_mk2)
* [Clustering](#analysis)<br><br>
Successes: Gained a solid understanding of important machine learning concepts. Saw success with certain classification models.<br><br>
Failures: Inaccurate linear models, poor visualizations.<br>
Limitations: Time. If I had more time, I believe I could have refined and tried different models and produced better visualizations.<br><br>
Improvements: As stated above, I would try different models and produce higher-quality visualizaitons.<br>
### Conclusions
Main findings: Produced a (relatively) succesful classifier model to predict a country's region. RandomForest performed the best, leveraging the advantages of a decision tree while reducing some of the variability that comes from randomly seeding only one tree. Also produced a relatively succesful predictive model to gauge a country's happiness based on certain metrics. Our performance can obviously be skewed by things such as world events, etc. but this model is relatively succesful at calculating a 'baseline' value for happiness.<br>
Story: I wanted to explore the machine learning concepts we have learned in class on a dataset that interested me, the Word Happiness Report. I wanted to see if it was possible to predict certain metrics about a country based on other values.<br>