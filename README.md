# 🍿 Analyzing Popular Movies on MovieLens 

## 📚 About Data

This dataset (ml-latest) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 33832162 ratings and 2328315 tag applications across 86537 movies. These data were created by 330975 users between January 09, 1995 and July 20, 2023. This dataset was generated on July 20, 2023.

Users were selected at random for inclusion. All selected users had rated at least 1 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

The data set is publicly available on [Kaggle](https://www.kaggle.com/datasets/whenamancodes/popular-movies-datasets-58000-movies?resource=download).

## 💡 Highlights

- Film-Noir is the highest rated genre of all-time despite being one of the least popular in terms of audience size.
- Drama is one of the most popular genres exceeding 5M ratings and an average rating of 3.79 
- Film-Noir has it roots as early as 1930s which is prevalent here. Despite having the least amount of ratings, it performed the highest with an average rating of 4.15. 
- 1940s is one of the strongest decades in film! It is also during the peak of Hollywood's Golden Age.
- The 1950s showed a high number of audience ratings across different genres.
- Another influential decade of cinema occured during the 2010s. With the rise of CGI and high-budget movies. Movies are produced in higher quality than ever before.

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Seperate years in the movies dataset into their own column
- Seperate genres into their own columns by One-Hot Encoding column
- Remove columns such as timestamp from ratings dataset since we will not be using it
- Reduce the number of reviews to less than 15M to be able to utilize in Tableau by removing rows where movie generes are not listed/available as well as their ratings

📍 Jupyter script: [Notebook](https://github.com/anamichell/Rating-Popular-Movies/blob/main/Popular%20Movies%20Dataset%20-%20Data%20Wrangling.ipynb)

📍 Clean Data: [movies_new.csv](https://github.com/anamichell/Rating-Popular-Movies/blob/main/movies_new%20(1).csv)
ratings_new.csv (unable to upload large file)

## 📊 Visualization

Produced a dashboard and story analysis walking through some highlights of the data.

Tableau: [Worksheet](https://public.tableau.com/app/profile/ana.garcia2226/viz/PopularMoviesWorksheet/PopularMoviesWorksheet?publish=yes)
[Story](https://public.tableau.com/app/profile/ana.garcia2226/viz/PopularMoviesWorksheet-Analysis/Analysis)

<img width="2798" height="1798" alt="Dashboard 1" src="https://github.com/user-attachments/assets/2af15ee1-440d-4b47-b2d3-96f32f1e3d91" />
