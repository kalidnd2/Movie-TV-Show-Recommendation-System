# Movie-TV-Show-Recommendation-System

Summary of Problem:

In 2021 most individuals living in the United States have used or are currently using some sort of
streaming service to watch movies and TV shows. There are a large variety of platforms on the
internet that allow for consumers to do this such as Netflix, Prime Video, Hulu, and HBO Max.
In fact, studies show that 70% of millennial’s use a streaming service on a weekly basis and 40%
confirm that they use them on a daily basis.

Due to the rapid growth in online streaming, a common problem many individuals have is deter-
mining which movie/show to watch next. Our project aims to implement a recommendation system
using Machine Learning to determine similar movies/TV shows using a variety of features including
genre, director, cast, and IMDB rating.



Approach:

Content based filtering and collaborative filtering are two techniques that can be applied to help
build this recommendation tool. Collaborative filter is a technique used by large streaming services
such as Netflix and Amazon which makes automatic predictions for users by collecting data from
the other users using their platforms. Collaborative filtering operates under the assumption that users
who agreed in their assessment of a certain movie/TV show will likely also agree in the future on
another movie/TV show. If you have used a streaming service, you might recall that underneath the
descriptions of movies/TV shows there is usually a snippet of text that states the following ”98% of
people who liked this movie also liked **blank**.” This is an example of collaborative filtering.

Content based filtering on the other hand is a technique which uses a user’s previous history to
provide a recommendation. Unlike collaborative filtering it does not use data obtained from other
users, just data from a single unique user. Content based filtering will use key-words and features
from a user’s input to output a recommendation.

For our project we chose to use a content based filtering approach simply cause we don’t have a
platform which gives us access to the data of a large number of users.
In the next section we will take a look at the flow chart for our project and discuss a bit more about
how we tackled the code for it.
