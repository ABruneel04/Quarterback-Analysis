# Quarterback-Analysis

This code uses the BeautifulSoup library to scrape fantasy football data for quarterbacks from 5 seasons (2016-2020). The link to the page where data was scraped from can be found here:
<br>https://www.fantasypros.com/nfl/stats/qb.php

<br><br>This project was a way for me to practice using web scraping to collect data and learn from it via visualizations and feature engineering. I begin by collecting the data from the table in the website linked above, and convert all of the relevant statistics into the correct type because they start as Strings. From there, I concatenate the DataFrames I create for each year into a single DataFrame, and group the data by 'Player' (and take the mean) so that I can get a wholistic view of the data across the time span.

<br><br>At first, I attempted engineer useful features such as the rank difference/fantasy point difference between each year and use a Naive Bayes algorithm to predict a player's ranking for a given year, but I found that the model was not as accurate as I wanted it to be, and would not be able to generalize well to future seasons. From there, I began to change direction and explore visualizations that would enhance my understanding of the data and how each predictor relates to one another. This will allow me to better define future steps for this project, and gave my practice with a valuable DS tool (data visualization).

<br><br>As I continue work with this project, I would like to be able to predict quarterback rankings for future seasons based on their past data. The next steps will be to add more data into this dataframe from other sources (e.g. if the player was injured during the season, the strength of defenses they played, etc.). With more relevant predictors for ML algorithms to learn off, I will be able to expand this project. For now, I also want to spend more time with visualizations on the data I already have.
