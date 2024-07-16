# HelloHarmony: Enhancing Music Recommendation and Discovery with Machine Learning and Artificial Intelligence

## By Sophia Mares, Manahil Nasim
### University of San Diego

## Project Overview
In this project, we aim to solve the problem of music recommendations for online music streaming services. The goal is to help users discover new music in a stress-free manner by creating a recommendation system that suggests music based on user preferences, listening habits, and trends.

## Dataset
The dataset used in this project is sourced from the HetRec 2011 dataset provided by GroupLens, which includes social networking, tagging, and music artist listening information from approximately 2,000 users on the Last.fm online music platform. The dataset consists of the following files:
- `artists.dat`: Information about music artists.
- `tags.dat`: Set of tags available in the dataset.
- `user_artists.dat`: Artists listened to by each user with listening counts.
- `user_taggedartists.dat` and `user_taggedartists-timestamps.dat`: Tag assignments of artists provided by users along with timestamps.
- `user_friends.dat`: Friend relationships between users.

## Features
### User Features
- Total listening count
- Unique artists listened
- Average listening count per artist
- Number of friends
- Peak listening hours
- Tag diversity
- Recency metrics

### Artist Features
- Total listening count
- Unique users listened
- Average listening count per user
- Number of tags
- Popularity trends
- Listener diversity
- Most influential tags

### Tag Features
- Number of users
- Number of artists associated with each tag

## Visualizations
Key visualizations include:
- Heatmap of User-Artist Interactions
- Bar plots of Top 10 Most Active Users and Most Popular Artists
- Scatter Plot of User-Artist Interactions
- Artist Growth Trends

## How to Use
1. Clone the repository.
2. Install the necessary libraries using `requirements.txt`.
3. Run the EDA and feature engineering scripts to preprocess the data.
4. Use the recommendation system scripts to generate music recommendations based on user preferences.
