# Music-Recommendation-System
This project involves leveraging data science techniques to build a recommendation system based on past rating data using AI-driven recommendation system techniques.

# Problem Definition
# The Context:
Music has always been a staple in society. For almost anyone, music can be an escape, an outlet, or an expression. It is probably one of, if not the, most interacted with form of media for many people. With the advent of streaming platforms, more music is accessible to people now than ever before.

As music becomes more accessible, it becomes even more paramount that companies can key on what will keep people interacting with their app and the music on their app more than ever. Not only companies like Spotify and Apple with Apple music, but artists as well rely on people interacting with these streaming platforms to generate revenue. With so many more songs becoming available, it's become quite tedious to continue to find music similar to one's tastes. That makes it even more important that users have functionality available to them that streamlines the process of them finding music within the app.

It's become quite clear throughout history that makng something more convenient for your user is the best way to drive engagement, and that's what makes recommendations on streaming apps like Spotify and Apple Music so important.

To that end, it becomes important to be able to ensure that their platforms do a good job of both making sure that users can interact with the music they enjoy as easily as possible, but also leveraging algorithms to be able to recommend new content to users to maintain and even increase engagement, both improving the app's quality and ease of use for the listener. The more time people spend on the app, the more revenue they generate and the more artists benefit as well.

# The objective:
To that end, the objective of this project is to develop a recommendation system leveraging data science techniques to predict the top 10 songs for a user based on how likely they are to listen to those songs.

This is based on a number of key factors, including what kinds of songs they've listened to the most, and their tendencies when it comes to listening to music in general.

This will increase user satisfaction and engagement by delivering personalized and accurate music recommendations, enhance the experience of a user by helping them navigating and ever increasing library of music.

# The key questions:
In general, we want to ensure that our recommendation system is as accurate as possible for a company to deploy to their users so that they can be connfident in the recommendations they're getting. A poor recommendation system would not only not benefit the users and the company, but would damage the reputation of the product and make users less likely to listen to music on that app. To that end, here are some key questions we want to answer?

What key factors contribute to a user's music preferences?
What data can we use to understand user preferences?
How do users display their like/dislike of music?
Do they not interact with old kinds of music?
Are there certain genres that users don't interact with?
How can we ensure that our recommendations are not only accurate, but precise?
How much error do we have in our recommendation system, and how egregious is said error?

# The problem formulation:
What is it that we are trying to solve using data science?
First, we will load, clean/process and understand the data we've been given in our datasets.

Then, we will use exploratory data analysis to try and identify key features that allow us to answer our first question above (what features can we identify that will allow us to understand a user's music preference).

Then, we will leverage the different kinds of Recommendation Systems we've learned in the past few weeks:

# Rank/Popularity based

# User/User collaborative filtering

# Item/Item collaborative filtering

# Model Based/Matrix Factorization

# Clustering based

# Content based

We will apply these models to the dataset, evaluate them, and try to identify which one is most effective in recommendation. We will use F1 score, RMSE, precision and recall values to evaluate the models.

We will internalize our results make a final recommendation on which recommendation system would be the best approach in improving user experience, thus improving the product.

# Data Dictionary

The core data is the Taste Profile Subset released by the Echo Nest as part of the Million Song Dataset. There are two files in this dataset. The first file contains the details about the song id, titles, release, artist name, and the year of release. The second file contains the user id, song id, and the play count of users.

song_data

song_id - A unique id given to every song

title - Title of the song

Release - Name of the released album

Artist_name - Name of the artist

year - Year of release

count_data

user _id - A unique id given to the user

song_id - A unique id given to the song

play_count - Number of times the song was played

# Data Source:
http://millionsongdataset.com/


