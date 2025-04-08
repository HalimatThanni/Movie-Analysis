# Movie-Analysis
<img src="NetFlix-Logo.png" width="1000" height="300">

## Project Overview

With the explosion of streaming services, understanding content trends and audience preferences has become crucial for media companies. This project analyzes a Netflix dataset to uncover patterns in movie and TV show releases, content distribution by country, popular genres, and other key insights.

## Objective

The primary objective of this project is to analyze Netflix’s content catalogue to uncover key trends and insights that can inform decision-making for content creators, media analysts, and business strategists. Specifically, Identify Content Distribution Patterns, Understand Genre Popularity, Analyze Content Growth Over Time, Evaluate Content Duration and Ratings, and Enhance Data Storytelling Through Visualization.
By achieving these objectives, this analysis provides a data-driven overview of Netflix’s content strategy and helps identify trends that may shape the future of the streaming industry.

## Key Questions

* Which countries produce the most content on Netflix?
* What genres dominate the platform?
* How has Netflix's content output changed over time?
* What is the distribution of content ratings and durations?

## Data Understanding

The dataset used for this project consists of Netflix's catalogue of movies and TV shows, containing 8,790 records with key attributes such as title, director, country, date added to Netflix, rating, duration, and genre classification. To enhance the analysis, additional columns were derived, including the year and month of addition, TV show duration (in seasons), and the number of days since a title was added.

## Exploratory Data Analysis (EDA)

An in-depth exploratory data analysis (EDA) was conducted to gain insights into the Netflix dataset. This involved data inspection, cleaning, and visualization to uncover patterns and trends. Below are the key steps carried out during the analysis:

#### 1. Initial Data Inspection:

  - Used df.head() to view the first five rows of the dataset.
  - Applied df.info() to check the datatype of each column, identifying any necessary modifications.

<img width="754" alt="df info()" src="https://github.com/user-attachments/assets/6093397a-b272-4785-b179-5d38b993baca" />

#### 2. Data Cleaning & Standardization:

  - Standardized the text columns (e.g., title, country) by correcting abbreviations and inconsistent spellings.
  - Converted date-related columns (release_year, date_added) to proper datetime formats, extracting relevant features like Year and Month for trend analysis.

