![microsoft.png](./images/microsoft.png)


# Microsoft Film Industry Analysis
## Overview
As a result of the rise in original film production in mega companies, Microsoft has tasked us with the responsibility to appraise her of the movie industry outlook before it climbs on the bandwagon. We used the return on investment as a measure to gauge the profitability of particular gernres, previewed the month of release of those perticular movies, looked into the genres that were most popular and those that had high viewer votes so we could come up with conclusions.

## 1. Business Problem
The potential business problem for Microsoft in deciding to enter the original video content space is determining how to create content that will stand out from competitors and attract and retain viewers. With established players such as Sony and Disney already producing stellar original content, Microsoft will need to differentiate itself and create compelling content that resonates with viewers to gain a foothold in the market by-

- investing significantly in content development, talent acquisition, and marketing,
- Gaining deep understanding of audience preferences and trends,
- Deciding on a monetization strategy that balances the costs of content creation with revenue streams such as subscriptions or advertising.

I based my analysis on 3 major factors

- When is the most favorable month of the year to release a movie?
- What is the relationship between production cost and revenues?
- What type of genres are most popular?

## 2. Data Understanding
This analysis utilizes datasets acquired from three movie websites, namely Box Office Mojo, The Numbers, and TMDB.

The first dataset, bom.movie_gross.csv, has five columns comprising of movie titles, studios, financial incomes both domestic and foreign and the release year.

The second dataset, tn.movie_budgets.csv, contains information on released films, including their names, release dates, and financial data such as production budget and worldwide gross. The key variable for this dataset is the ROI, and the monetary data columns are the primary reason for selecting this dataset.

The third dataset, tmdb.movies.csv, contains genre codes, original language of the movies, original movie titles, popularity metrics, dates in which the movies were released, and information on the votes. I used this dataset to map genre codes to genre names obtained from the same website so that I could see which genres are more trending.

## 3. Methods

I gathered reliable data from trustworthy sources and eliminated irrelevant data columns. I replaced any missing data with a value of 0. Additionally, I ensured that any information I used was from reputable sources and used both descriptive statistics and visual aids to identify patterns and important factors that contribute to successful movies. This methodology was suitable for examining trends in the film industry and identifying characteristics shared by high-earning movies, so I could provide well-informed suggestions.

## 4. Results

Based on the scatter plot analysis, the worldwide gross tends to increase as production budget increases.

![Production Budget vs Worldwide gross.png](./images/Production%20Budget%20vs%20Worldwide%20gross.png)


### ROI

Based on the scatter plot analysis, it is evident that there exists an inverse correlation between the production budget and the RoI, however, the relationship between the two is not linear. Specifically, for budgets ranging from 0 to 100 million dollars, there is a negative correlation between the RoI and the production budget. However, for budgets ranging from 100 to 300 million dollars, there seems to be no clear correlation between the two variables. 

![Production Budget vs Return on Investment.png](./images/Production%20Budget%20vs%20Return%20on%20Investment.png)

The movies released on the month of April had the highest ROI followed by September and July. Contrastingly, April and September trail last when it comes to the number of films released on those months. This explains why they have a higher ROI. July seems to be an interesting month for movie release since movies released in July have a relatively high ROI.

![Average ROI per Month.png](./images/Average%20ROI%20per%20Month.png)

![Distribution of films released per month.png](./images/Distribution%20of%20films%20released%20per%20month.png)


Genres with the highest number of movies were Drama, Action, Comedy, Adventure and  Thriller. However, genres such us History, Music, Mystrery and Thriller have a comparatively high ROI and low production and the reason behind it could be explained that these movies had fewer movies classified under them. Therefore ROI could not pinpoint the most yeilding genres to explore. 

![Average ROI by Genre.png](./images/Average%20ROI%20by%20Genre.png)

![Number of Movies per Genre.png](./images/Number%20of%20Movies%20per%20Genre.png)

### Popularity

I examined each movie in TMDB and categorized them according to their respective genres. Based on my analysis, I identified the seven most commonly occurring genres, which are 
1. Adventure
2. Action
3. Fantasy
4. Science Fiction
5. War

![Most Popular Genres.png](./images/Most%20Popular%20Genres.png)

After analyzing the data, I determined that the top five genres with the highest average rating (in terms of stars) are 
1. Music
2. History
3. War
4. Animation
5. Drama

![Average Vote by Genre](./images/Average%20Vote%20by%20Genre.png)

### Competitiveness

The top 5 studios in terms of gross income are
1. Walt Disney Studios
2. 20th Century Fox
3. Universal Pictures
4. Warner Bros. Pictures
5. Sony Pictures Entertainment (SPE)

![Top 10 Studios by Total Gross (2013-2018)](./images/Top%2010%20Studios%20by%20Total%20Gross%20(2013-2018).png)


## Conclusion

This analysis leads to the following recommendations for the types of films that are the best performing in the box office:
- Microsoft could obtain their intellectual property rights from any of this top movie studios, including Walt Disney, Universal Pictures, Warner Brothers, 21st Century Fox, and Sony Pictures Entertainment since it has no prior experience in film production.
- The Production Budget of a film has a weak positive correlation with its return on investment.
- The Worldwide Gross of a film has strong positive correlation with Production Budget. 
- Movies released in July are more likely to yield a higher return on investment.
- 'Horror' and 'Music' genres are more likely to have a higher return on investment but 'Action' and 'Adventure' films are the top most popular genres. Exploring the popularity of genres gives Microsoft way forward.





