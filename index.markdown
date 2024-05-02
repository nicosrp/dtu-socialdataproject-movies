---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Behind the Screens🎥: Decoding Patterns within the Movie Industry</h1>

Authors: Manos Loukaidis and Nico Sherpa

3, 2, 1... Action! Grab yourself some popcorn and enjoy the movie. The smell of cheese nachos, 2 liter coca cola cups, and 165 minutes pure entertainment. We all love movies, don't we? What do we really like, is it a specific genre, or the multi-million dollar CGI that has been used? With this project, how we perceive movies given a set of underlying assumption, and subsequently want to learn something about ourselves as humans. Let's dive right into it.

<iframe src="genreNetworkGraph.html" width="100%" height="400px" style="border:none;"></iframe>

Our chosen dataset, the [TMDB Movies Dataset](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies) contains data of exactly 1,030,001 movies. This data reaches from the title, release data, revenue, to the specifically assigned genres for each movie, and many more categories. Let's look a bit deeper into how many movies are assigned to each genre, and how people judged the specific genre differently. In the following plot, the assigned number of movies towards a specific genre, as well as the the average rating (average of all movies), as well as a weighted average rating (for each movie the average rating multiplied with the vote count, summed up and devided by the total vote count per genre; or the average of each single vote per genre).

<iframe src="genreNumberRatingBarplot.html" width="100%" height="600" style="border:none;"></iframe>

The Drama genre has been assigned the most with 214.583k assignments, followed by the Documentary (154.462k) and Comedy(132.107k) genre while only 8.560k movies have been assigned to the Western genre. What is interesting to see is that there is a very clear difference between the average and weighted average ratings for each genre. However, it makes sense if we assume that better movies are more popular and thus more often voted for in our dataset, consequently having a higher influence on the weighted average rating.

As recent events in the world confirm, humans apparently like war, maybe as they think it might be necessary, maybe because some find it entertaining. Our graph, however, seems to confirm the latter. With an average vote of 7.29 out of 10 is the War genre the highest rated amongst all genres, considering the weighted rating only. 



<iframe src="tSeries.html" width="100%" height="600" style="border:none;"></iframe>


The contribution split for this assignment can be found on the [About](https://nicosrp.github.io/dtu-socialdataproject-movies/about/) page.