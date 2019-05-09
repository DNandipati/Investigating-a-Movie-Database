# Date Created 
2019/05/04

# Project Title
Project 2: Investigating a dataset for TMDB

# Description
Analyzing the raw data set provided from Kaggle and exploring the data to determine any factors that influence the quality of a movie. This project involves thorough data cleaning, data wrangling and data visualization for many other variables present and answering specific research questions.

# Technologies Used
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

# Research Questions
 1. Has the budget been increasing with time? Plot the graph
 2. What are the most and least profitable movies? Formula of Profit = Revenue - Budget
 3. Have movies been getting popular with time? Plot the graph 
 4. What are the top 10 budgeted movies? Plot the graph
 5. What are the most succesful genres in TMDB. Plot the graph.
 6. Identify the top 5 directors according to the popularity of the movies and how many movies have they made?

# Key Findings
TDMB dataset provided great insights about movie data, from the budget, to cast, directors and many more useful information. From the research questions from this project, the concluding points noted were:
- Movie budgets have been drastically increasing with time along with the net profits being returned; we devised profit from the simple formula of revenue subtracting the budget
- The most profitable movie in this database was the Avatar with a whopping 2.5 billion dollars and the lowest profitable movie was "The Warrior's Way". Although Avatar is accurate, with further research it was shown that the statistics for the latter movie was actually incorrect.
- Data noted that movies have been getting more popular since 2010 and the returning profits are highly correlated
- we noted that Action movies were the most profitable genre in our database followed by Comedy and Adventure. This information can be useful for producers who maybe looking to invest in a movie.
- Through analysis, the top 5 directors were found. With Christopher Nolan directing 10 movies with the highest popularity rate of 61.95, followed by Steven Spielberg with 29 movies and popularity rate of 54.3
- With given analysis and data, one can note all the characteristics needed to have a profitable movie

This dataset however had problems and some of the information were not accurate. For example, the highest budgeted movie was shown to be "The Warrior's Way" with a budget of 425 million dollars, but in reality that movie budge was actually only 40 million. There are multiple errors in the dataset and limitations, dropping certain rows from cleaning might also have affected the results.

# Files used
Project2_Complete.ipynb| tmdb-movies.csv