# Boston AirBNB analysis
This repository manages to get some useful and interesting insights into Boston AirBNB data.  
data [source](https://www.kaggle.com/airbnb/boston)

## Business questions being answered
1. What is the price distribution of AirBNB homes?
2. How is price fluctuating over time?
3. How is demand changing over time?
4. What kinds of room layout are most popular?
5. What kinds of room layout receive highest ratings?
6. What do home owners emphasize in their descriptions?
7. What are most important things to tenants?

## Data
there are three .csv files of Boston AirBNB data.  
1. "calendar.csv".  
with columns of {"listing_id","date","available","price"}, it tells the price and availability of each AirBNB house on each day.  
2. "listings.csv".  
It has more than 80 columns and tells everything about each AirBNB house. Like ratings, descriptions, basic room layouts etc.  
3. "reviews.csv".  
It collected every verbal comments tenants made online, with columns {"listing_id","id","date","reviewer_id","erviewer_name","commnets"}.  

## General analysis process
As there is no modelling work in this analysi. All efforts are to data cleannign and exploration to answer business questions raised above. And  
most data wrangling work is put on "listing.csv". Missing values are interpolated or dropped based on my judgements. histogram, heatmaps, and  
wordclouds are adopted to better visualize the results.

## Blog
If you want to know more about my work. please go to [my blog](https://medium.com/@jlm3448179892009/get-to-understand-airbnb-at-boston-c254a4b50a26)

## acknowledgement
Thanks to teams from Udacity's Data Scientist Nanodegree who have made my learning path fascinating.


