# Lights, Camera, Data: Movie Statistics Over a Decade

In this project, we used data about movie popularity and Oscar winners to analyze factors that contribute to movie success and how awards and box-office performance are related.

### Data Gathering
* We scraped data related to Oscar awards from the following Wikipedia pages: 
    * [Best Picture wikipedia page](https://en.wikipedia.org/wiki/Academy_Award_for_Best_Picture)
    * [Best Actor](https://en.wikipedia.org/wiki/Academy_Award_for_Best_Actor)
    * [Best Actress](https://en.wikipedia.org/wiki/Academy_Award_for_Best_Actress)
* We gathered movie statistics from The Movie Database (TMDB) via API
     * [TMDB API](https://developer.themoviedb.org/reference/getting-started)
* We examined the following movie data:
    * Top 100 movies (by TMDB vote count) per year from 2015 - 2024
    * All movies nominated for a Best Picture between 2015 and 2024
    * All movies containing a cast member who was nominated for a Best Actor Oscar between 2015 and 2024

## Data Analysis
* We examined the following research questions. Each question has a corresponding Jupyter notebook in the notebooks folder.
    * How popular is each genre over the last decade? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/AE_Issue_3.ipynb))
    * How do budget and revenue vary by year or by genre? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/cdg_issue_5.ipynb)
    * What is the average profit margin (revenue - budget) across genres or years? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/JWT_issue_6.ipynb))
    * How do movie ratings (vote average) relate to box-office performance? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/cdg_issue_4.ipynb))
    * Adjust all financial metrics (budget and revenue) for inflation to 2024 dollars using CPI data. ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/AE_Issue_7.ipynb))
    * Do Best Picture nominees or winners tend to earn higher box-office revenue than non-nominated movies? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/JWT_issue_8.ipynb))
    * Are certain genres or types of roles more common among award-winning films? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/AE_issue_9.ipynb))
    * Do movies featuring a Best Actor or Best Actress winner in their cast tend to perform better? ([notebook](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/blob/main/notebooks/AE_Issue_10.ipynb))



## Final Presentation
* You will find the final presentation slides in [assets/Movie_Performance_Presentation.pdf](https://github.com/nss-data-science-cohort-9/webscraping-apis-movies-the-cranberries/tree/main/assets)
