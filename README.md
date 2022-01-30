# [Python Correlation Analysis of Movie Data](https://github.com/davidgomezpr1/Python_Correlation_Movie)
![](https://images.unsplash.com/photo-1542204165-65bf26472b9b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1074&q=80)

## Business Request

As a data analyst working for a film production company, internal stakeholders wanted me to dig into data for the past few decades of the film business to help them address their hypotheses. Bringing clarity to these, will have a significant impact on their company goals for the coming year.

The following hypotheses were provided for me to test:

- The `gross` earnings of a movie is strongly correlated to its `budget`.
- The `gross` revenue of a movie is strongly correlated to the the fame/size of the `company` that produced it.


## Overview

- Data covers four decades of movie data scraped from movie online database [IMDb](https://www.imdb.com/). Data was fetched from [Kaggle](https://www.kaggle.com/danielgrijalvas/movies).
- Exploring the dataframe.
- Data cleaning to prepare the `dataframe` for analysis (e.g. drop any rows with `null` values, splitting of column fields, etc.)
- Correlation analysis to test for the stated hypotheses.
- Analysis to identify the pairs of variables with a strong correlation.

## Conclusions

- A strong positive correlation was observed between the `gross` revenue and the `budget` of the films, confirming the first hypothesis. This was determined by a correlation coefficient (r) equal to 0.74.
- The film production `company` and `gross` revenue have a correlation coefficient of 0.15. This indicates a low correlation, which proves that the hypothesis was incorrect.
- It was concluded that `votes` and `budget` have the strongest correlation to `gross` revenue (0.61 and 0.74, respectively).
