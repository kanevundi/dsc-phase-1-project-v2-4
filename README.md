![microsoft.png](./images/microsoft.png)


# Microsoft Film Industry Analysis
## Overview
As a result of the rise in original film production in mega companies, Microsoft has tasked us with the responsibility to appraise her of the movie industry outlook before it climbs on the bandwagon. We used the return on investment as a measure to gauge the profitability of particular gernres, previewed the month of release of those perticular movies, looked into the genres that were most popular and those that had high viewer votes so we could come up with conclusions.

## 1. Business Problem
The potential business problem for Microsoft in deciding to enter the original video content space is determining how to create content that will stand out from competitors and attract and retain viewers. With established players such as Netflix and Amazon already producing stellar original content, Microsoft will need to differentiate itself and create compelling content that resonates with viewers to gain a foothold in the market by-

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


![Distribution of films released per month.png](./images/Distribution%20of%20films%20released%20per%20month.png)


![Average ROI per Month.png](./images/Average%20ROI%20per%20Month.png)


![Average ROI by Genre.png](./images/Average%20Vote%20by%20Genre.png)


![Most Popular Genres.png](./images/Most%20Popular%20Genres.png)


![Production Budget vs Worldwide gross.png](.\images/Production%20Budget%20vs%20Worldwide%20gross.png)












