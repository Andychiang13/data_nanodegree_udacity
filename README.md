# Udacity projects

This repo is a collection of all the projects did for the data analysis nanodegree program by Udacity.

List of projects:
* Investigate a dataset:
  * European Soccer Database Analysis.
  * The database is substracted from [Kaggle](https://www.kaggle.com/hugomathien/soccer), created by Hugo Mathien.
  * Using the database, I researched two questions:
    1. What is the correlation between player's age and overall scoring and potential scoring?
    2. How do teams' play styles correlate with goals through all seasons?
  * Used SQLite to retrieve data from the dataset.

* A/B test analysis
  * Data obtained from an A/B test run by an e-commerce website. The goal is to understand whether the new page is better than the old page.
  * The label for test is the *conversion* in the data, 1 for users that converted,  0 for not converted. 
  * After the initial analysis, additional factors: country factor for each user's origin, was added for the analysis to show if the users' origin influence the *conversion* or not.

* WeRateDogs analysis:
  * Data obtained from the twitter account WeRateDogs from 2015 to 2017, and filtered by Udacity's staff so the total number of tweets included in the *twitter_archive_enhanced* is 2356. Image prediction data also provided by Udacity course through a neural network that can classify breeds of dogs. Additional data was collected via Twitter API.
  * Whole process of data wrangling was performed in this project, which includes data gathering, data assessing, data cleaning, storing, analyzing and visualization.
  * Interesting findings are in the act_report.pdf.