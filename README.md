# VOIS_AICTE_Oct2025_MajorProject_Rohit_Wachnekar

This project analyzes the Netflix dataset to uncover trends in its content library. The primary goal is to understand the distribution of movies versus TV shows, identify popular genres, and see which countries contribute the most content. The insights from this analysis are used to provide strategic recommendations for Netflix's future content acquisition and production strategy.

## Project Objectives

Based on the project's problem statement, the key objectives are:

1. **Analyze Content Distribution**: Investigate the distribution of movies vs. TV shows over the years to see how the content mix has evolved.
2. **Identify Popular Genres**: Determine the most common genres available on the platform and analyze their prevalence.
3. **Compare Country Contributions**: Analyze and compare the amount of content produced by different countries to understand Netflix's global footprint.

## Dataset

The dataset used for this analysis is **Netflix Dataset.csv**, which contains information on 7,789 movies and TV shows available on Netflix as of 2021.

Key columns in the dataset include:

- **Category**: Identifies the content as either a 'Movie' or 'TV Show'.
- **Title**: The name of the movie or TV show.
- **Director**: The director of the content.
- **Country**: The country where the content was produced.
- **Release_Date**: The date the content was added to Netflix.
- **Rating**: The content's maturity rating (e.g., TV-MA, PG-13).
- **Duration**: The runtime for movies (in minutes) or the number of seasons for TV shows.
- **Type**: The genres the content belongs to.

## Tools and Libraries

This analysis was conducted using Python in a Jupyter Notebook-like environment. The primary libraries used are:

- **pandas**: For data manipulation and cleaning.
- **matplotlib & seaborn**: For data visualization and creating insightful plots.
- **warnings**: To handle and suppress non-critical warnings during execution.

## Analysis and Key Findings

The analysis was broken down into several steps, revealing the following key insights:

1. **Movies vs. TV Shows**
   - Netflix's library contains significantly more movies than TV shows.
   - However, the addition of new TV shows has grown at a very high rate since 2016, indicating a strategic focus on episodic content.

2. **Popular Genres**
   - The most dominant genres are "International Movies" and "Dramas", highlighting a focus on global content and mature storytelling.
   - "Comedies" also represent a significant portion of the library.

3. **Top Contributing Countries**
   - The United States is the largest single contributor of content.
   - India is a strong second, reflecting Netflix's investment in the Indian market. The United Kingdom and Japan are also major players.

4. **Content Ratings and Duration**
   - The most common rating is TV-MA (Mature Audience), showing a focus on an adult demographic.
   - Most movies have a standard runtime of 80-120 minutes.
   - A vast number of TV shows are single-season series, which could be a strategy for testing new concepts or producing limited series.

## Strategic Recommendations

Based on the analysis, the following strategic recommendations are proposed:

- **Invest in TV Shows**: Continue the aggressive investment in multi-season TV shows, as they are crucial for long-term subscriber retention.
- **Diversify Genres**: While dramas are popular, investing in underrepresented genres like Anime and Sci-Fi can attract different audience segments.
- **Expand Local Productions**: Deepen investment in local content in high-growth markets to cater to local tastes and source new "international" hits.
- **Target Families and Teens**: Increase the library of TV-PG and TV-14 content to make the platform more appealing for households.
