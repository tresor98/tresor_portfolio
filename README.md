# Tresor_portfolio

# [Project 1: Scraping reviews on Amazon](https://github.com/tresor98/amazon_scraping_reviews)
Scraping through reviews on amazon given a list of product ids.
The first code (amazon_reviews.ipynb) scrape syncronously thus is a bit slower
The second code(faster_webscraping) scrapes asyncrously thus going faster.

The code will fecth:
<ol>
  <li>Get through the pages of each product id comments section</li>
<li>Fetch each comment with its title, rating, verification status, author_url, author, review_date and the how many people found it helpful </li>
  <li>The code will go through all possible comments pages</li>
  <li>Comments related to each product id will be stored in a json file</li>
</ol>

It is recommend to use a VPN while using the codes for a better results.

You might need to rerun the code for the data that returned empty list as data for some product ids may not be fetched at the first attempt.

# [Project 2: IBM platinum deposit study case](https://github.com/tresor98/IBM-platinum-deposit)

The project aim is to be able to predict which customer will positively reply to the offer that will be given based on historical data from a previous campaign.

Based on the fact that the company wanted to minimize as much as possible the number of unsuccessful calls. Our principal target was to minimize the number of False positive.

Most of the plot could not be rendered when the file was uploaded, to view them download the notebook and open it in your local machine.

# [Project 3: Credit card customer segmentation](https://github.com/tresor98/credit-card-clustering)

Based on their different transactions behavior, the project segmented them in three clearly distinct group that could be easily explained.

To achieve this we use KMeans algorithm and used the elbow method and visualization to choose the k optimal number to assign to the algorithm, which would then correspond to the number of clusters.

# [Project 4: Real estate price prediction](https://github.com/tresor98/real_estate_price_prediction)

This was a simple regression project that aimed at predicting the price of houses given some of their features such the house age, the number of convience stores nearby, the distance to the closest metro station and its location(longitude and latitude).

# [Project 5: Chinese postman](https://github.com/tresor98/chinese-postaman-problem)

A simple application of shortest path 
