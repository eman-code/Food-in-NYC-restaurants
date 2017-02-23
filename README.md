# Text Analytics of NYC Restaurant Inspection Data and Food Reviews

What are the influential parameters regarding with our decision when we go to restaurants in large cities like New York? Is there joint relation between high standards required from restaurants and personal desires of customers?  
The motivation of this question is especially for meal related websites such as MEALPAL.com and also smart city communities. 
In my project, I would like to analyze and compare two sets of reviews, which one is related to NYC restaurant inspections, violations, and grades and another one includes Food Reviews dataset highlighting the interests of New Yorkers. The data will be collected from available datasets on the web from data.cityofnewyork.us and also the crawled data from Amazon reviews for the food. 
In this project, I work on text analytics using document clustering of the NYC restaurant inspection data with k-means algorithm and multidimensional scaling and TF-IDF techniques as well as topic modeling the food reviews of regular customers in Amazon to find in which aspects there are more and less similarities between people’s point of view and Municipality and healthcare department.
Early results show the difference in views of two resources where the restaurant inspection watches more the equipment, area, and food standards while Amazon reviewers’ concerns are more on the taste of food and price. Combination of these aspects can provide the optimum decision making.

The data source related to New York City restaurant inspections, violations, and grades can be found in:
(https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j)
The data of Amazon food reviews is published on SNAP (http://snap.stanford.edu/data/web-FineFoods.html).
The Amazon Fine Food Reviews dataset consists of 568,454 food.

Here are also a quick review of text analytic techniques that are used in this project:
•	tokenizing and stemming
•	transforming into vector space using tf-idf
•	calculating cosine distance between each document as a measure of similarity
•	clustering the documents using the k-means algorithm for inspection data
•	using MDS (multidimensional scaling) to reduce dimensionality for inspection data
•	topic modeling using Latent Dirichlet Allocation (LDA) for Food Review data
