## What can be called a 'good' movie?
My motive was not to classify movies into good movies and bad movies but to filter good movies from movies. I wanted to know what makes a movie good. In order to do so, I used a dataset tmbd 5000 movies from Kaggle that had information of about 5000 movies based on their imdb information. I decided to start with an assumption that every movie that recovers its budget is a good movie. Therefore, using OpenRefine, I took the most popular films (films with popularity above 120) and plotted their statistics.
![Popular Movie statistics](/popular movie stats.png)<br>
Upon checking the image above, it seems like 'not all popular films were able to recover their budget'. Moreover, there are movies like 'The Shawshank Redemption' and 'Fight Club' that were popular and had many votes from the audience though they were unable to recollect their budget.
![Fight Club](/1.PNG)<br>
![Shawshank Redemption](/2.PNG)<br>
There were also movies with not-so-many votes from the audience.
![](/3.PNG)<br>
![](/4.PNG)<br>
Then, I decided that I will call all the movies that had good ratings from audience as good movies because one of the main purposes of a movie is to entertain the audience. So, I decided to look for movies with the highest ratings possible. I was able to find few movies with ratings more than 9. So, I checked for movies more than 9 using OpenRefine.
![](/votes.png)<br>
However, there was one problem. Though, all the movies had ratings more than 9, there were few voters for those films (maybe around 1 or 2). There was not a single movie with ratings more than 9 if I looked for more number of voters.<br>
Therefore, I decided to consider movies with ratings more than 8, where the vote count is more than 1000, as good movies. Using OpenRefine, I chose movies with ratings more than 8 and votes more than 1000. With the new dataset I got, I plotted a line chart, comparing the budget, revenue of those films.
![](/final visualization.png)