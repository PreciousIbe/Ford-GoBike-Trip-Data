# (Ford GoBike System Data)
## by (Ibe Nchedochukwu)


## Dataset


> This dataset includes information about individual rides made in a bike sharing system covering the greater San Francisco Bay Area. There are 183,412 data entries in the dataset with 16 columns(duration sec, start time, end time, start station id, start station name, start station latitude, start station longitude, end station id, end station name, end station latitude, end station longitude, bike id, user type, member birth year, member gender, and bike share for all trip.

> For the Data wrangling, first I assessed the data using df.head(), df.info() and df.describe().
Then I moved on to cleaning the data: I created a copy of my dataset, made changes to my member birth year, first by filling the null values with the mean and then creating a new column to get their actual age then converted it to an integar. Then I dropped the null values on my dataset. I also found the Duration in Minutes by dividing the duration_sec by 60 and converted it to an integar.
After cleaning, the total entries on my dataset went down to 174,952 and the columns changed to 18.

>I used univariate, bivariate and multivariate distributions to explore the data and get an indepth overview of my dataset.


## Summary of Findings

>I will briefly list my findings below:

> Subscribers and Customers are around the age group pg 20 to 45

>People aged 20 to 40 years used the bikes for all trips

>Majority of the younger age groups did not make it to 200minutes and a few of them got to 1,400

>Most males were subscribers of the bike sharing scheme

>Other genders took more trips than females and males

>Majority of the people aged 20-50 years were subscribers and customers, they also used their bikes for a long period of time.

>People aged 0-35 that were subscribers used their bikes for all trips, people that did not use thier bikes for all trips consisted of both customers and subscribers.


## Key Insights for Presentation

> Majority of the people aged 20-50 years were subscribers and customers, they also used their bikes for a long period of time.

>People aged 0-35 that were subscribers used their bikes for all trips, people that did not use thier bikes for all trips consisted of both customers and subscribers.