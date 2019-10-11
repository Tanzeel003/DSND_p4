# Learnings on analyzing the Seattle airbnb datasets

Understand lodging services in Seattle using Airbnb data

*Using CRISP-DM (Cross-Industry Standard Process for Data Mining), investigate Seattle Airbnb data and answer the following questions.*

1.	Which is the most popular neighborhood in Seattle? And similarly which is the least popular area in Seattle? What can we tell by looking at their monthly pricing trends?
2.	How does price fluctuate over time? Is there any seasonal effect over pricing?
3.	What are the main amenities? There will be many in the catalog but we will try to find the main profiles
4.	What are the different features that decide the pricing?
5.	Can we classify the properties? It would be nice to see what features bring the properties together and what separates them


### Software Requirements and Libraries used

* Python 3.x
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Time


### Project Instructions

1. Install required packages.
2. Clone the repository (including data)
3. Run Seattle_Airbnb notebook file.


### Motivation for the project

Airbnb is an online marketplace which lets people rent out their properties or spare rooms to guests. Since the company launched in 2009, it’s grown from helping 21,000 guests a year find a place to stay to helping six million a year go on holiday, and currently lists a staggering 800,000 properties in 34,000 cities across 90 different countries. In this project we will analyze the home stay datasets from Seattle, WA (USA).


### Files in the repository

We got the data from Kaggle. There were primarily three datasets provided to us, viz:
1. Calendar: This gives us the information whether the property is available for a certain period or not; If it is available the cost involved in blocking the property is also mentioned
2. Listings: This dataset tells us about the property. It will also provide information about owner’s credibility, property quality, occupancy, etc.
3. Reviews: This dataset provides reviews that users gave over time.


### Results

Through this project we went through Seattle Airbnb dataset and created some visualizations to understand what are the major popular areas in Seattle are. We also understood the following:
1.	Most popular may not be holding many properties for rent
2.	Average prices per properties are trending upward
3.	Better rated neighborhood have average prices higher than that of Seattle, probably better amenities are being provided
4.	Amenities such as TV, family friendliness, fire extinguisher are driving reasons for higher prices

### Acknowledgment

1. Earlier udacity projects
2. charts and its colors from matplotlib site (https://matplotlib.org/3.1.1/tutorials/colors/colors.html, https://matplotlib.org/api/pyplot_api.html)
3. Kaggle website to rpovide the dataset (https://www.kaggle.com/airbnb/seattle/data)



#### Blog post:
https://medium.com/@haidertanzeel003/we-analyzed-seattle-airbnb-data-heres-what-we-learned-f6393089f805?sk=584c78eb599df420d4c84c56d6eb2fdc
