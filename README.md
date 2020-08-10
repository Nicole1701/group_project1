### Topic: Analysis of Movie Box Office Data

**Team:**
* Nicole Cook
* Hermela Mekonnen
* Rob Savage
* Franklin Troung


**Tasks:**
* Pulling original data requests and merging data: Rob
* Cleaning data sets: Rob/Franklin
* Create DataFrame with cleaned data set & downloading to csv: Rob/Franklin
* Create 6-8 visualizations of data and save as PNG files: Nicole, Hermela, Franklin
* Analyze cleaned data set for any additional analysis: Team
* Create PowerPoint Presentation: Rob
* Presentation: Team


### Questions of Importance
* Do popular genres change over time?
* Does the audience’s taste for genre change over time?
* Do seasons have an effect on the metrics of a movie?
* Do seasons impact runtime and audience ratings?
* Has movie revenue (adjusted for inflation) fluctuated through the decades?
* Does duration  have any impact on the financial success of a movie?


### Data Sources
* IMDb movies extensive dataset: 
https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset
* Box Office Mojo: https://data.world/eliasdabbas/boxofficemojo-alltime-domestic-data


### Other things to take into consideration
* Revenue will need to take into account inflation
* Since movies can belong to more than one genre, we will need to have a separate stacked data set for this comparison


# Data Analysis


## Average Revenue Over Time

* Insert analysis here

## Rating Impact on Average Revenue

* Insert analysis here

## Impact of Duration on Revenue

* Insert analysis here

## Popular Genres Over Time

* There is not a lot of variation in the top genre's released over time. Drama  and Comedy have been the top two genres for the last 50 years. There is a little variation in the rest of the top 5, they have included Action, Romance, Crime, Thriller and Adventure (see Genre % Table)

* Dramas make up about 23% of movies released each decade, while comedies make up about 17% of movies released each year.

![Popular Genre's Over Time](images/Percentage_Genre_Over_Time.png)

* But the most popular genres don't necessarily translate into ratings. The highest rated movies of the last 50 years are biography, history and Animation tend to be rated highest (see Ratings Table)

* Looking at the most popular genres over time, their overall ratings tend to be rather consistent, except for the 1970's where movies tended to be rated higher all over. 

![Rating of Popular Genre's Over Time](images/Rating_by_Genre_Over_Time.png)

## Impact of Seasonality on Average Revenue/Ratings/Duration

* Movies released in winter tend to be higher rated than any other season, while movies released in summer tend to be lower rated. 

![Average Rating of Movies by Season](images/Rating_by_Season.png)

* Movies released in summer bring in the most revenue overall, while autumn tends to bring in the lowest revenue.

Revenue_by_Season

* Movies released in the winter have longer run times than those released any other time of year. 

![Average Movie Duration by Season](images/Duration_by_Season.png)