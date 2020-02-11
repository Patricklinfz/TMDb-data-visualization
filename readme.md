# Exploration of TMDB Movie Data

## Dataset
The TMDB movie data is and originally from [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata/data). The dataset contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings, budget, revenue. The dataset also covers a duration from 1960 to 2015.

## Summary of Findings
In exploration, popularity has a long-tailed distribution. A large amount of films falls on the low popularity end. Average vote shows a unimodal distribution that slightly left skewed. Big part of the data falls between 5 to 7.

Both the number of movies released and the number of horror movies have an overall trend of increase from 1960 to 2015. I also zoom in to look at percentage of horror movies in all movies by year since 2004. The trend is upward as well. It started from less than 10% back in 2004 to almost 20% in 2015. It shows horror genre had been increasing its market share. Movie-makers were motivated to make more horror films for the market.

I use average vote and popularity to compare horror and non-horror films via violin plots and box plots. In terms of average vote, horror genre is less favorable. Non-horror films exceeds horror films in average vote, with larger minimum, maximum, first quartile, third quartile and median of the distribution; regarding popularity, both median values falls way behind 1, suggesting a general low popularity. 

I further investigate horror vs. non-horror films in average vote and popularity by decade. In every decade, the average vote and popularity of non-horror films is always higher. The average vote of non-horror films appears to be quite consistent over the decades while horror films rendered decreasing audience approval. For the past two decades when horror films increased in both absolute number and percentage, the genre cannot stop falling in average vote and popularity.

## Key Insights for Presentation
I start by showing the distribution of popularity and average vote as a context. To see the major part of distribution in popularity, I change the ceiling value from 10 in data exploration to 6.

I then plot a series of line charts including number of films by year, number of horror films by year, percentage of horror films by year starting from 2004 to step-by-step unfold the growth of horror films in market share. For this part, I add better annotation to make sure points of interest are easily observed from number of films by year. Because understanding the overall gorwth is foundamental before moving on to look at just horror films in selected years.

For comparison between non-horror and horror films, average vote by decade and popularity by decade are sufficient for the audience approval of horror films. 

