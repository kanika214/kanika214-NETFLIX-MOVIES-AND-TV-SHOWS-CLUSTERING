# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
![image](https://user-images.githubusercontent.com/18574968/204129095-a6b90c3b-8eb9-4555-825f-33dc7a9c7989.png)

NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING 
based on unsupervised machine learning algorithms.
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

# Problem Statement

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Our goal here is to make an unsupervised clustering model, which will help in garnering insights on Netflix and how its content is being consumed.

A brief summary of the dataset is given below:


![image](https://user-images.githubusercontent.com/18574968/204129141-102ca804-9ff2-458a-b1c8-4ac0d0380912.png)


# Design and Methodology
In this section, we will discuss the framework, extraction and preprocessing features, feature selection, and clustering algorithms.

# Exploratory Data Analysis
The first step involved in the analysis is to load the dataset into the panda’s data frame. Before exploring the data using different libraries available in python we should if the dataset is ready to run the operations on it.

❖	Data Cleaning: Data Cleaning is one of the important steps before we start building models, in fact, there will be a significant increase in Model Performance when we have a clean, rich dataset. So here, we decided to replace null values with an empty string.
●	There are 2389 null values in Director column
●	There are 718 null values in cast column
●	There are 507 null values in country column
●	There are 10 null values in date added column

