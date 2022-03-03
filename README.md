
# Project Title : ZOMATO RESTAURANT CLUSTERING AND SENTIMENT ANALYSIS
![image](https://user-images.githubusercontent.com/93859458/153649982-bc8cfcb8-0436-4a0d-8502-01533a89a556.png)
## Description
In this project We collected our two datasets from almabetter platform,we merged datasets on common columns 'name' and 'restuarant' and created new dataset as df. more than half of values from the collection column were missing, we have'nt removed all values, instead of removing NULL value we tried to fill values by others.in preprocessing we removed unwanted columns and moved to Exploratory data analysis,we started clustering of our data in k number of cluster. to find a perfect number of cluster we are using different algorithms like silhouette score, Elbow method etc. In sentiment analysis we are categorizing our rating into two types bad and good. Then using sklearn pipeline module implementing MultinomialNB,LogisticRegression,DecisionTreeClassifier and Random forest Regression

## Table of Content
* Dataset Information
* Tools and Libraries Used
* Files
* Results
* Screenshots
* Business Summary
* Feedback


## Dataset Informatio
This dataset contains information on Names, Links, cost, collection, cuisines, Timings, Restaurents, Reviewer, Review, Rating, MetaData, Time and pictures. To cluster a data points and for sentiment analysis.

### Dataset 1 :

Name : Name of Restaurants
Links : URL Links of Restaurants
Cost : Per person estimated Cost of dining
Collection : Tagging of Restaurants w.r.t. Zomato categories
Cuisines : Cuisines served by Restaurants
Timings : Restaurant Timings
Dataset 1 Link:-https://raw.githubusercontent.com/samarthgangurde01/zomato-sentiment-analysis/main/Zomato%20Restaurant%20names%20and%20Metadata.csv


### Dataset 2 :
Restaurant : Name of the Restaurant
Reviewer : Name of the Reviewer
Review : Review Text
Rating : Rating Provided by Reviewer
MetaData : Reviewer Metadata - No. of Reviews and followers
Time: Date and Time of Review
Pictures : No. of pictures posted with review
Dataset 2 Link:-https://raw.githubusercontent.com/samarthgangurde01/zomato-sentiment-analysis/main/Zomato%20Restaurant%20reviews.csv



## Tools and Libraries Used
* Pandas
* numpy
* Matplotlib
* Seaborn
* plotly
* sklearn
* scipy
* nltk
* wordcloud


## Files
* This repository contains files as mentioned below
* zomato sentiment analysis.ipynb: Google colab contains all the python code, documentation and visualization
* Zomato Restaurant names and Metadata.csv: 1st_dataset 
* Zomato Restaurant reviews.csv: 2nd_dataset 


## Results
### For TFIDF

            Model	        | Accuracy
            
0	MultinomialNB	          |   72%

1	LogisticRegression      |   90%	

2	DecisionTreeClassifier  |   79%

            3 Random forest Regression|   99%

### For Bag Of Words

            Model	               | Accuracy
            
0	MultinomialNB	   |   90%

1	LogisticRegression        |   98%    

2	DecisionTreeClassifier    |   79%

3            Random forest Regression  |   66%



## Screenshots
![image](https://user-images.githubusercontent.com/93859458/153644903-11d8307b-1107-4a87-97af-9297fce16160.png)
![image](https://user-images.githubusercontent.com/93859458/153645015-725805bf-b549-47a1-a528-971ebf114863.png)
![image](https://user-images.githubusercontent.com/93859458/153645515-796d2125-ef15-447f-8426-332421a5820d.png)
![image](https://user-images.githubusercontent.com/93859458/153645618-878e41d9-fa2b-45ac-9828-c6b87dee5468.png)

## Power Bi Report

![image](https://user-images.githubusercontent.com/93859458/156638588-daa2ba29-22fc-4bb8-b5e3-13fe35002c0f.png)

Link :-https://app.powerbi.com/groups/me/reports/59b97260-cae7-43c6-a538-a3f4a4078e06/ReportSection?ctid=7762530d-7592-41e7-836b-c96c3705db76

## Business Goal:
The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solve some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis

## Feedback

If you have any feedback, please reach out to us at samarthgangurde01@gmail.com.com

