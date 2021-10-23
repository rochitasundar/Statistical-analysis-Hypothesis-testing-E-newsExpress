## Background
An online news portal aims to expand its business by acquiring new subscribers. Every visitor to the website takes certain actions based on their interest. 
The company plans to analyze these interests and wants to determine whether a new feature will be effective or not. 100 users are divided equally into two groups. 
The old landing page is served to the first group (control group) and the new landing page is served to the second group (treatment group). Various data about 
the customers in both groups are collected in 'abtest.csv'.

## Objective:
  - Explore the dataset and extract insights using Exploratory Data Analysis.
  - Do the users spend more time on the new landing page than the old landing page?
  - Is the conversion rate (the proportion of users who visit the landing page and get converted) for the new page greater than the conversion 
    rate for the old page?
  - Does the converted status depend on the preferred language?
  - Is the mean time spent on the new page same for the different language users?

## Data Dictionary:
  - user_id - This represents the user ID of the person visiting the website.
  - group - This represents whether the user belongs to the first group (control) or the second group (treatment).
  - landing_page - This represents whether the landing page is new or old.
  - time_spent_on_the_page - This represents the time (in minutes) spent by the user on the landing page.
  - converted - This represents whether the user gets converted to a subscriber of the news portal or not.
  - language_preferred - This represents the language chosen by the user to view the landing page.
