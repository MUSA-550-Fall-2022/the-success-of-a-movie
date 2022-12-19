
# Film Data Analysis

For this project, we would like to discover the significant factors that contribute to the general success of a movie. We will be looking at the relationship between the gross box office/revenue and features like movie genre, Oscars nominations/award, reviews, soundtrack ratings, and trailer popularity.

The data analysis and machie learning were based on the following datasets:  

Oscars data, ["_The Oscar Award, 1927 - 2020_" ](https://www.kaggle.com/datasets/unanimad/the-oscar-award).
          
YouTube trailers, ["_MovieLens 20M_"](https://grouplens.org/datasets/movielens/20m-youtube/) and scraped from [_YouTube_](https://www.youtube.com/watch?v={})
          
scraped Movie soundtrack data from ["_MOVIE WAVE_"](http://www.movie-wave.net/reviews-by-title/).


# 1. Discover Which Film Genre Is Most Likely To Receive The Honor?

Every January, countless of movie enthusiasts will be thrilled to find out which movie will receive the Oscars Academy Award, the highest honor in filmmaking! 
Based on our analysis, the number of awards nominations is correlated with the gross revenue. Consequently, we assume that the higher the gross revenue of a movie is, the more likely it is be a great film. 

![nomination vs gross](/assets/img/Nominationsvs.Total Gross.png)



In order to test our assumption, we searched for movies that have most Oscar nominations and movies that made remarkable gross revenue across the world. Then, We collected the genre types of these movies to get help us to develope a better answer.     

![revenue vs genre](/assets/img/genre-gross.png)

After we combined the domestic and abroad gross revenue, the result showed that drama films are on the top of our list and the revenue generated is almost three times more than the comedy movies, which is the second on our list. 

The result was reasonable, there can be a lot of complex storytelling with a lot of depth in drama films. No doubt that many people across the world would be attached to the movie and laugh, cry, think throughout the movie. 

![oscar vs genre](/assets/img/genre-oscar.png)

The Oscar Nominations plot shows Oscar nomination count, which is summed and grouped by genre. The three genres from the data with the highest number of Oscar nominations are Drama, Documentary, and Comedy. This suggests that films falling into these three genres tend to get nominated the most for Oscar awards. 

### Conclusion:
In conclusion, we found out that dramas and comedies perform the best in terms of movie success. It is also worth to mention that drama films also received the highest number of Oscar nominations. In the machine learning section, we will inlcude genere as one of the predictors in our model based on the large correlation between drama and success of a movie.



# 2. How does Trailer Popularity Affect Movie Success?

Before every movie is in theaters, there will be multiple versions of trailers released on social media and streaming platforms. The function of a trailer is to promote the film and marketing campaign. In this section, we did an exploratory analysis the significance of movie trailers on gross revenue and return on investment. 

After cleansing and wrangling the scraped data,   
![budget vs invest](/assets/img/invest-budget.png)

xxx

![trailer vs revenue](/assets/img/grossreve-trailer.png)

xxx


# 3. Do Music Scores Contribute to Movie Success?

![music vs imdb](/assets/img/imdb-music.png)

xxxx

![composer vs rating](/assets/img/composer-rate.png)

xxxx

![ROI vs genere](/assets/img/roi-genre.png)

xxxx

# 4. Machine Learning Model for Movie Success Prediction

<img src="assets/img/avater.png" width=670 height=450>
xxxx


<img src="/assets/img/james.png" width=350 height=200>
xxx


<img src="/assets/img/sam2.png" width=350 height=200>

<img src="/assets/img/zoe2.png" width=350 height=200>
xxxxx
