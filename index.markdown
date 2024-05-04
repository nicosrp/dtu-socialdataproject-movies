---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Behind the Screens🎥: Decoding Patterns within the Movie Industry</h1>

Authors: Manos Loukaidis and Nico Sherpa

3, 2, 1... Action! Grab yourself some popcorn and enjoy the movie. The smell of cheese nachos, 2 liter coca cola cups, and 165 minutes pure entertainment. We all love movies, don't we? What do we really like, is it a specific genre, or the multi-million dollar CGI that has been used? With this project, we want to investigate, how we perceive movies given a set of underlying assumption, and subsequently want to learn something about ourselves as humans. When we perceive things in a specific way, and information about that is documented, we can learn not only a lot about the documented industry, but also about societal trends and how we reflect ourselves in the documented data. So let's dive right into it.

<iframe src="genreNetworkGraph.html" width="100%" height="400px" style="border:none;"></iframe>

Our chosen dataset, the [TMDB Movies Dataset](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies) contains data of exactly 1,030,001 movies. This data reaches from the title, release data, revenue, to the specifically assigned genres for each movie, and many more categories (24 parameters in total). Let's look a bit deeper into how many movies are assigned to each genre, and how people judged the specific genre differently. In the following plot, the assigned number of movies towards a specific genre, the average rating (average of all movies), as well as a weighted average rating (for each movie the average rating is multiplied with the vote count, summed up and devided by the total vote count per genre; or the average of each single vote per genre).

<iframe src="genreNumberRatingBarplot.html" width="100%" height="600" style="border:none;"></iframe>

The Drama genre has been assigned the most with 214.583k assignments, followed by the Documentary (154.462k) and Comedy(132.107k) genre while only 8.560k movies have been assigned to the Western genre. As we can also see in the Network Graph from the beginning, the Drama genre has relatively many strong ties to other genres like Comedy or Thriller, and due to the fact that many movies have at least a bit 'drama' in their plot, this high occurance is not surprising. What is interesting to see is that there is a very clear difference between the average and weighted average ratings for each genre. However, it makes sense if we assume that better movies are more popular and thus more often voted for in our dataset, consequently having a higher influence on the weighted average rating.

As recent events in the world confirm, humans apparently like war, maybe as they think it might be necessary, maybe because some find it entertaining. Our graph, however, seems to confirm the latter. With an average vote of 7.29 out of 10, the War genre is the highest rated amongst all genres, considering the weighted rating only. The least rated one is the horror genre, which is not surprising if we think that a lot of people consider horror movies to be 'too scary', and the ones that like them might be hard to scare and base their rating on how much they got scared and not on how good the storyline is.

As a take away we can say, that humans love drama, otherwise drama would not be that important for movies. Humans, however, also like what war movies tickles in them, which is brutality, proudness, thrill of battle, but also to be able to distinguish between good and also to be secure in a comfortable home at the same time. We get a grasp of the excitement of war while not having to bear the risk to die. It might be interesting to see, in which other fields than movies we can observe these essential human traits. This might give us tremendous insights into what we like, what we want to gain out of something, and how humans can get influenced.

FIRST BUILD IN MOVIES OCCURRENCE OVER TIME???

<iframe src="tSeries.html" width="100%" height="600" style="border:none;"></iframe>

In this graph, showing genres and their ratings, we can see the difference between the animation and the horror genre over time (other genres are selectable by clicking on the legend). We can observe, that especially before 1940 the horror genre tends to be higer rated than animation movies. This trend shifts quite notably in the ealry 1980's, where the animation clearly outrates the horror genre. The [US animation explosion](https://en.wikipedia.org/wiki/History_of_animation#1980s) and deregulation of childrens cartoons by the Reagan administration could have had an influence on that, and might have been the starting shot for a spread and popularity increase in the animation genre. This might give us an idea, that the way how a society behaves is often determined by the frameworks in which a society lives. Would the animation boom have happened if there has not been this deregulation, would war movies be less interesting for us if the world would not be scared by two big world wars and a multitude of previous and past wars that have happened or ar still taking place. In which other ways did those occurances influence our society. Are we missing out on a huge boom that could have happened right now but the specific frameworks are not given? Those frameworks are also determined by different cultures. In the following world map, we can see how some specific measures in the movie industry differ around the world.

<iframe src="worldMap.html" width="100%" height="550" style="border:none;"></iframe>

TEXT TEXT TEXT
TEXT TEXT TEXT

<iframe src="average_runtime_over_decadesNew.html" width="100%" height="550" style="border:none;"></iframe>

TEXT TEXT TEXT
TEXT TEXT TEXT

The contribution split for this assignment can be found on the [About](https://nicosrp.github.io/dtu-socialdataproject-movies/about/) page.