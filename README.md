# Recommendations-with-IBM
This is the third project of Udacity Nano degree in Data Science. 
# Installation
Python 3.x is required to run this Project. The following libraries are used:
* Pandas
* Numpy
* Matplotlib
* Pickle

# Project Motivation
The goal is to develop a recommendation engine using rank-based, user-user based, and matrix factorization, and suggest new articles to the IBM Watson Community users.
# File Description
This project has four parts:<br/>
## I. Exploratory Data Analysis<br/>
Find out the distribution of articles a user interacts within the dataset and provide a visual and descriptive statistics.

## II. Rank Based Recommendations<br/>
Based on number of interactions, two functions of get n top articles names and n top articles ids are created.

## III. User-User Based Collaborative Filtering <br/>
Create the function of create_user_item_matrix to pivot the df dataframe. The rows are users and the columns are articles.<br/>
* Each user should only appear in each row once.<br/>
* Each article should only show up in one column.<br/>
* If a user has interacted with an article, then place a 1 where the user-row meets for that article-column. It does not matter how many times a user has interacted with the article, all entries where a user has interacted with an article should be a 1.<br/>
* If a user has not interacted with an item, then place a zero where the user-row meets for that article-column.<br/>

## V. Matrix Factorization <br/>
Use SVD method to conduct matrix factorization and make article recommendations to the users on the IBM Watson Studio platform.<br/>

## Licensing, Authors, Acknowledgements
This project is licensed under the terms of the MIT license. Credits must be given to IBM for providing the original datasets of the info of articles and users.
