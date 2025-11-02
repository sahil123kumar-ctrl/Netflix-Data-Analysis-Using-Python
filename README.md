# Netflix Data Analysis Using Python

## Project Overview
This project explores the **Netflix Titles dataset (as of 2021)** to uncover patterns, trends, and insights about movies and TV shows available on Netflix.  
Through data cleaning, transformation, and visualization, the analysis focuses on content distribution across countries, genres, release trends, and audience ratings — offering a data-driven view of Netflix’s evolving global strategy.

---

## Objectives
1. Analyze content growth trends (Movies vs TV Shows) over the years.  
2. Identify top contributing countries and their content evolution.  
3. Explore genre distribution, ratings, and release year patterns.  
4. Understand regional preferences and content diversification strategies.  
5. Provide actionable recommendations for Netflix’s content strategy.

---

## Dataset Information
**Dataset Name:** Netflix Titles (2021)  
**Source:** Kaggle — *Netflix Movies and TV Shows Dataset*  
**Size:** ~8,800 records  
**File:** `netflix_titles.csv`

### Dataset Columns Overview
| Column Name  | Description                               |
| ------------- | ------------------------------------------ |
| show_id       | Unique identifier for each title           |
| type          | Indicates whether it’s a Movie or TV Show  |
| title         | Name of the Movie or TV Show              |
| director      | Director of the title                     |
| cast          | Main cast involved                        |
| country       | Country of production                     |
| date_added    | Date when it was added to Netflix         |
| release_year  | Year of original release                  |
| rating        | TV rating (e.g., TV-MA, PG, R)            |
| duration      | Duration of the title                     |
| listed_in     | Genre(s)                                  |
| description   | Short summary of the content              |

---

## Tools & Libraries Used
| Category               | Libraries Used                          |
| ---------------------- | ---------------------------------------- |
| Data Manipulation      | pandas, numpy                            |
| Data Visualization     | matplotlib, seaborn, plotly              |
| Data Cleaning          | datetime, re                             |
| Environment            | Jupyter Notebook                         |

---

## Exploratory Data Analysis

### 1. Prerequisite Steps for Data Analysis
| Step No. | Step Name                                  |
| -------- | ------------------------------------------ |
| 1        | Importing Necessary Libraries              |
| 2        | Loading and Reading the Netflix Data File  |
| 3        | Checking Data Shape                        |
| 4        | Data Cleaning                              |
| 5        | Checking Datatypes                         |
| 6        | Dropping Duplicates                        |
| 7        | Understanding Data (info and summary)      |

---

## Problem Statements

### 1. Distribution of Types
Analysis of how Netflix content is divided between Movies and TV Shows.

### 2. Temporal Distribution of Netflix Content
1. Distribution of Netflix content over the years  
2. Content added to Netflix per year and per month  
3. Growth of Movies and TV Shows over years, months, quarters, and weekdays  

### 3. Country Insights
1. How is Netflix’s content distributed across countries?  
2. Which countries produce more Movies vs TV Shows?  
3. Top 10 countries producing the most Movies  
4. Top 10 countries producing the most TV Shows  
5. Growth of Netflix content in leading countries over the years  

### 4. Genre Insights
1. Most common genre on Netflix  
2. Most popular genre in the top 10 content-producing countries  
3. Year-wise top genres for leading countries  
4. Genres with the highest growth between 2016 and 2020  

### 5. Director Insights
1. Most popular directors across the top 10 content-producing countries  
2. Directors focusing mainly on Movies  
3. Directors focusing mainly on TV Shows  
4. Directors working across multiple genres  
5. Titles with a single director  
6. Titles with multiple directors  
7. Title with the highest number of directors  
8. Comparison of multi-genre vs specialist directors  

### 6. Rating Insights
1. Distribution of Netflix content ratings  
2. Distribution of ratings by type  
3. Average movie duration by rating  
4. Average TV show seasons by rating  
5. Country producing the most adult-rated content  
6. Country producing the most family-friendly content  
7. Country producing content across all ratings  
8. Months producing the most mature content  
9. Common ratings among top directors  
10. Growth of ratings in leading countries over time  

### 7. Duration Insights (Movies and TV Shows)
1. Count of movies with duration between 90–120 minutes  
2. Movie with the highest duration  
3. Movie with the shortest duration  
4. TV show with the highest number of seasons  

### 8. Release Year vs Added Year Insights
1. Maximum and minimum release years  
2. Maximum and minimum years when content was added to Netflix  
3. Titles that took the longest to appear on Netflix after release  
4. Titles released on Netflix before their official release date  
5. Titles with the same release and added year  

---

## Conclusion
Netflix’s content library shows **steady global expansion after 2015**, led by the **United States, India, and the United Kingdom**, with strong emerging contributions from **Japan, South Korea, and Pakistan**.  
Movies still dominate, but **TV Shows have grown rapidly**, driven by Netflix’s original productions.  
Genres like *International Movies*, *Dramas*, and *Comedies* form the backbone of viewer engagement.  
Ratings like **TV-MA** and **TV-14** dominate, reflecting a tilt toward mature audiences.  
Overall, Netflix has evolved from a **U.S.-centric catalog** into a **diverse global platform**, adapting content to regional tastes and audience behavior.

---

## Recommendations to Increase Engagement
1. **Expand Regional Originals:** Focus on localized stories in fast-growing regions (India, Pakistan, Japan, South Korea) to attract new audiences.  
2. **Diversify Genre Mix:** Increase investment in Romantic, Reality, and Documentary content with strong cross-cultural appeal.  
3. **Balance Content Length:** Experiment with short and mid-length formats to engage casual viewers.  
4. **Season Optimization:** Release more content during Q3 (summer) and December holidays to match peak viewing periods.  
5. **Promote Family-Friendly Content:** Develop more PG and TV-G titles to attract families and younger audiences.  
6. **Director and Creator Collaborations:** Encourage collaborations with versatile directors to produce varied and high-quality content.  
7. **Leverage Personalization:** Use analytics to tailor recommendations by country, rating, and genre to boost watch time and retention.

---


[LinkedIn / Portfolio link here]  
[Email if you’d like to include one]
