# Python_ExploratoryDataAnalysis
This is a repository created for EDA exercise using Python, NumPy, Pandas, Matplotlib and SeaBorn packages.

We are having the data for the 100 top-rated movies from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online. In this assignment, We will try to find some interesting insights into these movies and their voters, using Python.

**Insights and Inferences:**
Scatter plot above shows that there is a relation between movie budget and movie profit, but it is not linear or straight line, means it is not like that only higher budget is a guarantee of higher profit. There are movies having low budget and earning good profit, like movie "Deadpool" having budget of $ 58 million and generating profit of 
$ 305 million, while movie "The Hunger Games: Catching Fire" is having budget of $ 130 million and generating profit of $ 294 million.

Also, top 10 movies with highest profit are released after year 2010 which can be concluded that there are multiple avenues for movies to generate more business other than only cinemas like satellite rights, online streaming platforms etc.
Another observation is, if we look at actor1, actor2 and actor3 for these top 10 movies, there is hardly an actor, who has starred in multiple movies, which means movie profit is not dependent on any specific actor.
In addition, all top 10 movies belong to only 2 genre named "Animation" and "Action".
There are some movies which are showing negative profit. We need to find out what is the real reason for generating negative profit.

There are 3 movies, 27, 14 and 8, having 3 popualr actors having considerable number of likes.

        Title                      actor_1_name        actor_2_name    actor_3_name          actor_123_likes
        27     Inception                  Leonardo DiCaprio   Tom Hardy       Joseph Gordon-Levitt  79000.0
        14     X-Men: Days of Future Past Jennifer Lawrence   Peter Dinklage  Hugh Jackman          76000.0
        8      The Dark Knight Rises      Tom Hardy           Christian Bale  Joseph Gordon-Levitt  73000.0

"Leonardo DiCaprio", "Tom Hardy" and "Joseph Gordon-Levitt" having total likes as 79000.0 and individual likes as 29000, 27000 and 23000 respectively.
