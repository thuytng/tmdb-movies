# TMDb-movies

The dataset used in this analysis is The Move Database (TMDb), which contains info on movies from the year 2001 to 2015. In this analysis, I'll be exploring trends in movie ratings, particularly how what factors have an influence on voter ratings.

## View

View analysis.ipynb to see project.

## Methods of Analysis

1. Probability
2. Bootstrapping a sample for A/B testing
3. Logistic regression

## Data

First

|    |     id | imdb_id   |   popularity |    budget |    revenue | original_title               | homepage                                            | director         | tagline                       |
|---:|-------:|:----------|-------------:|----------:|-----------:|:-----------------------------|:----------------------------------------------------|:-----------------|:------------------------------|
|  0 | 135397 | tt0369610 |     32.9858  | 150000000 | 1513528810 | Jurassic World               | http://www.jurassicworld.com/                       | Colin Trevorrow  | The park is open.             |
|  1 |  76341 | tt1392190 |     28.4199  | 150000000 |  378436354 | Mad Max: Fury Road           | http://www.madmaxmovie.com/                         | George Miller    | What a Lovely Day.            |
|  2 | 262500 | tt2908446 |     13.1125  | 110000000 |  295238201 | Insurgent                    | http://www.thedivergentseries.movie/#insurgent      | Robert Schwentke | One Choice Can Destroy You    |
|  3 | 140607 | tt2488496 |     11.1731  | 200000000 | 2068178225 | Star Wars: The Force Awakens | http://www.starwars.com/films/star-wars-episode-vii | J.J. Abrams      | Every generation has a story. |
|  4 | 168259 | tt2820852 |      9.33501 | 190000000 | 1506249360 | Furious 7                    | http://www.furious7.com/                            | James Wan        | Vengeance Hits Home           |
