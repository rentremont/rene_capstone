# Disney Movies

## Google Slides presentation
Link: https://docs.google.com/presentation/d/e/2PACX-1vQdqTkVQBUO6Cz1RQQ7EIZJ-fBmYw1vVEaczOOU2gp-QSj7lhLbo6MNa86BDWpcshMo_6IzMiFN9xA4/pub?start=false&loop=false&delayms=3000

## Tableau Dashboard
Link:https://public.tableau.com/views/disney_dashboard-final/Story1?:language=en-US&:display_count=n&:origin=viz_share_link

## Table of Contents
* [Tableau Dashboard](#Tableau-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

## Motivation:
My motivation for this is my 11 year old daughter. We have been watching a marathon of the Marvel movies this summer, her first time seeing all of these movies, and she is obsessed with the storylines. It made me think about how not too many years ago, she was obsessed with only the animated films like Frozen and Encanto and watching them 20 times a day. The amount of money I spent on Disney animated movies for her is probably far too much, but am I now entering a more expensive era?


## Questions:
1) Which style of movie brings in more money for Disney, animated films or live action films? 
2) Was the outcome different prior to Disney acquiring the Marvel and Star Wars universes?
3) Does factoring in the cost of inflation influence the outcome?
4) Did the number of theaters each style was released in have an influence on the outcome?
5) What are the most successful films for each style?
6) Was the acquisition of the Marvel and Star Wars universes worth the amount of money Disney paid?




## Normalizing the Data
I utilized webscraping to acquire most of my data through websites like boxofficemojo.com, natoonline.org (National Association of Theatre Owners), and Imdb.com (International Movie Database). I created several dataframes under each category (live, animated, marvel, etc.) and merged them together to create a master list. I created a separate dataframe with ticket pricing information with the average price of a ticket for each year and what the adjusted price would be today based on inflation. 


## Problems and Hurdles
Webscraping the data was challenging, especially if the data on the site was not already in a table format. Movies made before 1982 did not have all the information listed like the more modern movies do. Before 1982 they do not list how many theaters the movie was shown in, and most often did not report on the opening weekend statistics. 


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) Tableau - for creating interactive dashboard
3) Google slides - for introduction of Project


## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis

1) boxofficemojo.com for tables on each brand of Disney movie (marvel, star wars, pixar, etc.)
https://www.boxofficemojo.com/brand/bn3732077058/?ref_=bo_bns_table_1

3) natoonline.org (National Association of Theatre Owners) for ticket price information
https://www.natoonline.org/data/ticket-price/

5) Wikipedia for more ticket price information
https://en.wikipedia.org/wiki/Box_office)

6) Imdb.com (International Movie Database) for a complete list of Disney movies
https://www.imdb.com/list/ls033609554/?st_dt=&mode=detail&page=1&ref_=ttls_vm_dtl&sort=release_date,asc

## Conclusion
Disney purchased Marvel for $4 billion in 2009. It has since made over 13 billion dollars for Disney.  It has become one of the highest-grossing media franchises of all time. Needless to say, they have gained a significant amount for their investment, and it was a wise purchase. Disney acquired Lucasfilm in 2012 for $4.05 billion. The movies Disney has produced for Star Wars since then have made about 3 billion dollars, but still a wise investment. Considering that Marvel has made over 23 movies and Star Wars has only made 5, the return on their investment from strictly the movie side has not equaled what they paid for it. However, factoring in the merchandise, tv shows, and theme park, I would say they have more than made up the difference and it was a very wise investment on their part. 