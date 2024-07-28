# Film-Industry-Profitability
This is a project to assess the success of various films based on genres, directors, and ratings with profitability as the dependant variable.

## Data And Buisness Understanding
Karasha Films ants to start a original content film buisness and has tasked us in checking the data from three websites to determine which types films are most successful.
'Types' refer to genre however we will also recommend possibe directors and release dates if they deem relevant to profitability and success.
### Approach To Data Handling
1. Import data
2. Explore data
3. Clean Data
4. Analyse Data with Visualisations
5. Model the data
6. Interpret the results
7. Give recommendations based on the interpretations

The data sources are as highlighted below:
1. [IMDB website](https://www.imdb.com/)
2. [The Numbers website](https://www.the-numbers.com/)
3. [Box Office Mojo](https://www.boxofficemojo.com/)

After importing and cleaning the data, i checked for normal distribution 
within the data: I used a histogram to show the distribution of gross_profit

Performed a IQR test after noticing the data was highly skewed and had high kurtosis

The data is somewhat normalised but not enough to do any normal ttests. Due to this well be using the following tests on our Hypotheses;

..* Spearman's Rank Correlation
..* Kruskal-Wallis H test

I did an analysis of the following datasets in our dataframe;
1. Genres
2. Release Date
3. Directors
4. Production Budget
5. Average Rating per film

The hypothesis tested were as follows:
1. Does the combination of genres affect the profitability of the film?
2. Does Release Date Influence Opening Weekend Box Office Success and to what significance?
3. Does the number of films done by a director affect the profitability of the film?
4. Does Production budget have an effect on how profitable a combination of genres will be?
5. Does average rating affect how profitable a film will be?

## In Conclusion
From this dataset and Hypothesis tests we can suggest the studio create films which have the following characteristics.
1. Be an Action Adventure combination with an additional theme of Drama, Comedy SciFi and Sport genres.
2. Hire experienced directors with more than 1 film in thier professional background preferably Steven Speilberg.
3. Use thier part of thier production budget to influence the rating of the film before release to get a rating of 7.5 and above.

I believe these recommendations will be the best first step in creating a successful film buisness based on the data provided.
