# Netflix-Data-Analysis-Using-Python

## Project Overview

This project explores the Netflix Titles dataset (as of 2021) to uncover patterns, trends, and insights about movies and TV shows available on Netflix.
Through data cleaning, transformation, and visualization, the analysis focuses on content distribution across countries, genres, release trends, and audience ratings — offering a data-driven view of Netflix’s evolving global strategy.

## Objectives

1.Analyze content growth trends (Movies vs TV Shows) over the years.
2.Identify top contributing countries and their content evolution.
3.Explore genre distribution, ratings, and release year patterns.
4.Understand regional preferences and content diversification strategies.
5.Provide real-world recommendations for Netflix’s content strategy.

## Dataset Information
Dataset Name: Netflix Titles (2021)
Source: Kaggle — Netflix Movies and TV Shows Dataset
Size: ~8,800 records
File: netflix_titles.csv

## Dataset Columns Overview:
| Column Name  | Description                               |
| ------------ | ----------------------------------------- |
| show_id      | Unique identifier for each title          |
| type         | Indicates whether it’s a Movie or TV Show |
| title        | Name of the Movie or TV Show              |
| director     | Director of the title                     |
| cast         | Main cast involved                        |
| country      | Country of production                     |
| date_added   | Date when it was added to Netflix         |
| release_year | Year of original release                  |
| rating       | TV rating (e.g., TV-MA, PG, R)            |
| duration     | Duration of the title                     |
| listed_in    | Genre(s)                                  |
| description  | Short summary of the content              |


## Tools & Libraries Used
| Category               | Libraries                                      |
| ---------------------- | ---------------------------------------------- |
| **Data Manipulation**  | `pandas`, `numpy`                              |
| **Data Visualization** | `matplotlib`, `seaborn`, `plotly`,  |
| **Data Cleaning**      | `datetime`, `re`                               |
| **Environment**        | Jupyter Notebook                               |




## Exploratory Data Analysis:

### 1. Prereqisites Steps for Data Analysis:

| **Step No.** | **Step Name**                             |
| ------------ | ----------------------------------------- |
| 1            | Importing Necessary Libraries             |
| 2            | Loading and Reading the Netflix Data File |
| 3            | Data Shape
| 4            | Data Cleaning                             |
| 5            | Checking Datatypes                        |
| 6            | Dropping Duplicates                       |
| 7            | Understanding Data (info and summary)     |



## Problem Statments:

### 1. Distribution of Types.

### 2. Temporal Distribution of Netflix Content:

1.Distribution of Netflix Content Over the Years.

2.Content Added to Netflix per Year and per Month.

3.Growth of Movies and TV Shows Over the Years.

4.Growth of Movies and TV Shows Over the Months.

5.Growth of Movies and TV Shows Over the Quarters.

6.Growth of Movies and TV Shows Over the Weekdays.


### 3. Country Insights:

1️ How is Netflix’s content distributed across different countries?

2️ What type of content (movies or TV shows) does each country produce the most?

3️ Which countries dominate in producing the top 10 movies on Netflix?

4️ Which countries dominate in producing the top 10 TV shows on Netflix?

5️ How has Netflix’s content grown in the leading content-producing countries by type over the years?

### 4.Genre Insights:

1.Most Common Genre on Netflix:

2. Most Popular Genre in the Top 10 Leading Content-Producing Countries.
   
3.Year-wise Top Genres on Netflix for the Top 10 Leading Countries.

4.Genres on Netflix which experienced the highest growth in content additions between 2016 and 2020?

### 5. Director Insight:

1.Most Popular director by the top 10 Netflix Content Producing Countries.

2.Most Popular director who mainly focus on movies

3.Most Popular director who mainly focus on TV Shows

4.Directors who worked in most genres

5.Find out the titles with single director

6.Find out the titles with multiple director.

7.Find out the title with the highest number of directors.

9.Multigenre vs Speicalist Direcotors.


### 6. Rating Insight:

1.Distribution of Netflix Content Ratings.

2.Distribution of Rating by Type.

3.Average Duration of Movies by Rating.

4.Average Seasons of TV Shows by Ratings.

5.Country Producing the Most Adult-Rated Content.

6.Country Producing the Most family friendly content.

7.Country Producing Content Across All Ratings.

8.Months producing the most matured content.

9.The most common ratings among the top 10 highest content-producing directors

10.Growth of Ratings in Top Content-Producing Countries Over the Years


### 7. Distribution of Duration for Movies and Tv Shows.

1.Count the number of movies whose duration is between 90 to 120 minutes:
   
2.Find out the movie with highest duration in min:
   
3.Find out the movie with shortest duration in min:
   
4.Find out the Tv shows with the highest number of Seasons.


### 8.Insights on Movies and TV Shows: Release Year vs. Added Year on Netflix”

1.Maximum year of content release.

2.Minimum year of content release.

3.Maximum year content was added to Netflix.

4.Minimum year content was added to Netflix.

5.Netflix title which took the longest year to stream on Netflix before its release date.

6.Netflix titles that were streamed on Netflix first and later released in theaters.

7.Number of Netflix titles whose release year and date added year is same.


## Conclusion:

Netflix’s content library shows steady global expansion after 2015, led by the United States, India, and the United Kingdom, with strong emerging contributions from Japan, South Korea, and Pakistan.
Movies still dominate the platform, but TV shows have grown rapidly, especially after Netflix’s investment in originals.
Genres like International Movies, Dramas, and Comedies form the backbone of global engagement, while TV-MA and TV-14 ratings dominate Netflix’s catalog,
reflecting a tilt toward mature audiences.
Overall, Netflix has evolved from a U.S.-centric catalog into a diverse, global platform, adapting content to regional tastes and audience behavior.


## Reccomendations to Increase Engagement:

1.Expand Regional Originals:
Focus on localized stories in fast-growing regions (India, Pakistan, Japan, and South Korea) to boost engagement and attract new audiences.

2.Diversify Genre Mix:
Increase investment in Romantic, Reality, and Documentary content, which show strong cross-cultural appeal and steady growth.

3.Balance Content Length:
Since most movies range between 90–120 minutes, experiment with short-form and mid-length content to cater to casual viewers.

4.Season Optimization:
Release more content during Q3 (summer) and December holidays, when viewer activity peaks.

5.Promote Family-Friendly Content:
Although mature-rated content dominates, producing more PG and TV-G content can attract family audiences and younger demographics.

6.Director and Creator Collaborations:
Encourage collaborations with multi-genre directors (like Anurag Kashyap and Martin Scorsese) to create diverse, engaging titles.

7.Leverage Data for Personalization:
Use advanced viewing pattern analytics to tailor recommendations by country, rating, and genre — boosting watch time and retention


