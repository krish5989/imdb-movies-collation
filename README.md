# imdb-movies-info-collation
*__author__: Krishnan*

### Use case:

Whenever I wanted to relax and watch a movie, I always wasn't sure which one to pick. Though there is a lot of information available on IMDB, Google search, etc I had to spend lot of time browsing through these sites to find a good movie to watch. It was hard to find all the information in one place. There was also no aggregated information which I could quickly lookup. That's when I thought of creating a simple Excel sheet with an exhaustive list of movies that had all necessary information (about the rating, genre, votes, and streaming information) to help make a quick decision. You might ask why Excel? It's a simple and easy solution that will help us to apply various filters and lookup aggregated data on laptops, desktops, and mobile phones, etc. Compatible with google sheet, MS Excel and Numbers (iOS). With these capabilities i felt it was the best option to choose.

This repository contains a notebook, *imdb-analysis.ipynb*, which ingests IMDB movie collection data and enriches it with streaming availability information for movies, and outputs an aggregated Excel sheet. In addition to quick lookup on what movie to watch, this repository also helps us to understand how to read a compressed tab-separated file (TSV) using the Pandas library. We can also learn how to clean the column names in a dataframe, apply appropriate data types, and merge two dataframes in Pandas. The notebook also covers some simple analysis and filterations which can be done using pandas and numpy libraries.



### Dataset information:
The dataset used in this repository is from **IMDB** website. For data dictionary details please click [here](https://www.imdb.com/interfaces/)

dataset can be found here: [datasets](https://datasets.imdbws.com/)

`Streaming information data is added to this repository but doesn't contain for all the movies that avilable on IMDB dataset. ref: MoviesOnStreamingPlatforms_updated.csv`


### Data filter condition:
```
* Movies released after 2010 i.e. 2011 - 2022.
* Movies with avg_rating > 7.0
* Movies with num_votes > 5000
```

### Sample output:

Screenshot from the output excel sheet:

![Excel Output](/Users/sukakrish/krish-workspace/imdb-movies-analysis/excel_output.png)

