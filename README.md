# Anime Analysis And Recommanding System
## Group 2: Yuchen Chang & Jingwen Qiu

### I. Description
Every animation content has its own viewers and each content has it's rating.
Viewers leave some good ratings for the content if they like it. But what about a new viewer facing tremendous ratings and comments of a specific kind of content? How will they know what to try?
Businesses need to provide suggestions based on viewers likings and needs in order to create a better animated environment that boosts revenue and increases the time spent on a website. So we made a basic app like this to satisfy such business needs and values.

### II. Original Dataset
Our raw database is from [Anime Recommendations Database in Kaggle](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database)
It originally contains seven types of data, including id, name, genre, type, episode, rating, rating member.

### III. Questions & Analysis
Since we find more and more viewers pay attention to the validity of ratings and which genre they will like, we come up with two questions below to figure out what is going on.

- **Q1**: What is the relationship between rating and rating members?
- **A1**: From selecting different 5000 samples, it’s not difficult for us to find that low rating has more rating members and high has less, so there might be a negative association between them. In other words, those higher rating scores of some animations are decided by less people. From the perspective of rating validity and credibility, high score doesn't mean fascination. Even though so many viewers take ratings as their only standard, we are here to suggest that viewers should take more things into consideration. For example, you can also choose the genres you like.

- **Q2**: What is the most popular genre?
- **A2**: The chart we made shows the numbers of anime that have the genre tags within the range that the users selected with filtering widgets. We can find out the most popular genre is comedy. If viewers are hesitated to determine what sorts they will like, they still can take the outcomes of this question into account. Just imagine! If you a beginner in Japanese animation and feel puzzled to decide where to begin your journey of anime, it might be a good idea to try one of the most popular genres.

### IV. Functions
*Our app can satisfy user diverse needs based on widgets including*:
- choose different rating scores
- choose different genres
- choose different episode lengths

*Our app can deploy diverse visualization results based on plots and charts including*:
- a bar plot and a dataframe of rating members based on the range users choose
- a horizontal bar plot to describe the number of different genres
- a pie chart of each type's proportion
- a distribution histogram and trending line of all the ratings




