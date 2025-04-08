# Movie-Analysis
<img width="1000" height="300" alt="NetFlix-Logo" src="https://github.com/user-attachments/assets/7340d21c-3683-4dca-95a1-25eff4143aa3" />


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
  - I applied df.info() to check the datatype of each column and identify any necessary modifications.

<img width="754" alt="df info()" src="https://github.com/user-attachments/assets/6093397a-b272-4785-b179-5d38b993baca" />

#### 2. Data Cleaning & Standardization:

  - Standardized the text columns (e.g., title, country) by correcting abbreviations and inconsistent spellings.
  
<img width="575" alt="Standardise Title column" src="https://github.com/user-attachments/assets/c7c889f2-53cc-4272-a238-80ab1afe4c8d" />

 - Converted date column (date_added) to proper datetime formats, but first took care of unwanted parentheses.

<img width="557" alt="Date column" src="https://github.com/user-attachments/assets/9947cf09-448a-4854-8e44-66aa95d17cc5" />

  -  Extracted relevant features like Year and Month for trend analysis.

<img width="454" alt="Extract Year and Month" src="https://github.com/user-attachments/assets/48d8c30e-62f1-465e-ad63-6782c7001e09" />

#### 3. Handling Missing Values:

  - Identified missing values in key columns and addressed them accordingly.
    
<img width="351" alt="Missing values" src="https://github.com/user-attachments/assets/955ff046-8ba8-4316-88a8-85bad6d82b89" />
    
  - Filled missing values with 'NIL'.

<img width="511" alt="Fill missing values" src="https://github.com/user-attachments/assets/3a48ff31-be84-4979-882a-0e859a6b7a05" />


## Modeling
### Data Visualization:

- Popular directors: Visualized the top 10 most popular directors using bar plots.

<img width="355" alt="popular director" src="https://github.com/user-attachments/assets/7e1e531b-42d8-4b30-8537-291cd4e83ef5" />

<img width="632" alt="chart of popular directors" src="https://github.com/user-attachments/assets/5624f1bd-d13f-42e0-bc2c-a6f0bc046a4c" />


###

- Producing Countries: Visualized the top 5 countries producing movies using bar plots.
  
<img width="398" alt="Top 5 countries" src="https://github.com/user-attachments/assets/f121d19c-2dd0-46f8-8646-4b87b9e86101" />

<img width="564" alt="chart top 5 countries" src="https://github.com/user-attachments/assets/217bd439-dbff-4dba-86b8-308c07d077e4" />


###

- Yearly Trend: Visualized movie/show trends over the years using line plots.

<img width="399" alt="Movie trend" src="https://github.com/user-attachments/assets/7f325ef0-03a2-4d69-a893-25bd824957ca" />
  
<img width="579" alt="Chart movie trend" src="https://github.com/user-attachments/assets/1ade962f-33a3-4b1d-980e-95f5a8a73241" />


###

- Country Genre Mix: Visualised the most popular country genre mix using a bar plot

<img width="450" alt="country genre mix" src="https://github.com/user-attachments/assets/4272bb61-eb6a-48c2-bb5a-6d99d0c07ab9" />

<img width="578" alt="chart country genre mix" src="https://github.com/user-attachments/assets/a58323c4-4c15-40ec-aba5-7a41c35823a6" />


###

- Popular Movie Genre: Visualised the most popular movie genre on Netflix using a bar plot

<img width="568" alt="popular movie genre" src="https://github.com/user-attachments/assets/d5da78f1-ed65-4bb7-b223-2509974bb122" />

<img width="606" alt="chart popular movie genre" src="https://github.com/user-attachments/assets/23f6ebd0-4e5b-4cbc-9a7c-f3e9c63fe9cf" />


###

- Average Movie Duration: Visualised countries with the highest movie duration using a bar plot

  <img width="500" alt="Avg movie duration" src="https://github.com/user-attachments/assets/95582646-fd04-4929-9c4f-5f74e077b694" />

  <img width="575" alt="chart avg movie duration" src="https://github.com/user-attachments/assets/b9ac3335-baa0-4c13-92f2-84db7969e053" />


## Evaluation

Key Findings:

- Most content originates from the U.S. and India, with the U.S. leading significantly in movie/show contributions.
- Content release peaked in 2019 with over 2,000 titles, followed by a drop post-pandemic.
- Top 3 genres on Netflix: International Movies, Dramas, and Comedies.
- TV Shows account for about 30% of the content, many being limited series with just 1–2 seasons.
- Rajiv Chilaka is the most featured director, followed by Raúl Campos & Jan Suter, and Alastair Fothergill.
- Countries with the longest average movie durations include Croatia, West Germany, and the Soviet Union.
- India favors International Movies, while the U.S. prefers Dramas, Comedies, and Documentaries.
- Most common content ratings: TV-MA, TV-14, and TV-PG, indicating a skew toward mature audiences.
- Missing values were found mostly in the title, date added, and duration columns and were addressed during cleaning.
- A new feature was engineered to calculate days since content release, revealing that most content was added in the past 5 years.
