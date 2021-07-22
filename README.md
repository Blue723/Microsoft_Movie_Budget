# README

![cinema](img\microsoftimg.png)

# Overview

Microsoft is interested in analyzing if the production budget has a relationship or affect with a movie's average rating, popularity, and profit. They hope to conclude production budget is a significant variable in having a successful movie. 

# Business Problem

Microsoft would like to have a production budget less than $100 million while having a successful movie. Microsoft has minimum values for  average rating(7.5), popularity(12.693), and profit(150%) for what they consider a “success” in each category. We will compare production budget relation on average rating, popularity, and profit separately to observe relation and trends. 
 

# Data

Microsoft has given data on movies on past movies to analyze budget. Extracted data used on movie’s budgets under 100 million and compared to:
 - Average ratings with minimum rating of 7.5 and number of votes 10,000, 
 - Popularity more than 12.693 (the top 75% rated values)
 - Worldwide gross to calculate profit more than 150%


# Methods

This project uses correlation analysis to look for trends that find how budget is related to other data. 

![cinema](img\cinemaimg.png)

# Results

 - There appears to be no relationship between a movies production budget under 100 million and avrage rating, popularity, or profit percentage. 
 - Looking at the top 20, as expected from the correlation above, production budget appears to have no effect on profit percentage.

![results](img\budg_rating_scatter.png) ![results](img\budg_rating.png) 

![results](img\budg_pop_scatter.png) ![results](img\budg_pop.png) 

 ![results](img\budg_profit_scatter.png) ![results](img\budg_profit.png)

# Conclusion

Since the results do not show any relations or effects from one variable to another, Microsoft can conclude:
 - The budget will not determine a movie’s profit.
 - Focusing on making a movie popular will not affect profit or ratings
 - Ratings is not indicative of a profitable movie. 

Next Steps: 
 - Microsoft will want to address other possible indicators of profit returns.
 - Since having good ratings, popularity, and low budget are not indicators of profit. Perhaps looking into studio, genre, or director. 
 - Look into other relations between ratings, popularity, and budget to other data given. 
