Netflix Data Cleaning, Analysis and Visualization:

Project Goal: The objective of this project was to clean, analyze, and visualize the Netflix content library to uncover insights about its composition, growth, and focus areas.

Step-by-Step Implementation:

Step 1: Data Cleaning and Preparation

We loaded the netflix1.csv dataset and performed an initial exploration, identifying columns with missing data.

We systematically handled missing values in the rating, director, and country columns.

We debugged a KeyError, discovering that the cast and description columns were not present in the user's specific file, and adapted our plan accordingly.

We transformed the date_added column into a proper datetime format and extracted the year and month for analysis.

Step 2: Exploratory Data Analysis and Visualization

We analyzed and plotted the distribution of Movies vs. TV Shows.

We visualized the growth of content added to the platform over the years, noting the sharp increase after 2015.

We determined the Top 15 Genres and Top 15 Countries by splitting combined fields to get accurate counts.

We analyzed the distribution of Movie Durations and the most common number of Seasons for TV Shows.

Step 3: Advanced Predictive Modeling

At your request, we built two separate, advanced models as a logical next step.

Classification Model: We created a model to predict if a title is a 'Movie' or 'TV Show' based on its director, country, and genre information.

Recommendation System: We built a content-based recommendation system that suggests similar titles to a user based on shared genres.
