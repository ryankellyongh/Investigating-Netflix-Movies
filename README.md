# Netflix Movies Investment Analysis


## Exploring 1990s Netflix Movies Through Data Analytics

**Project Overview**

Netflix has grown from a DVD rental company into one of the largest entertainment and media platforms in the world. With thousands of movies and series available, it provides an excellent opportunity for exploratory data analysis. 

This project focuses on analyzing Netflix movies released during the 1990s. Approaching the dataset from the perspective of a production company interested in nostalgic content and investment opportunities, the goal is to identify patterns in movie duration, genre trends, and characteristics that defined successful films of that decade.

The analysis helps answer questions such as:

• What was the most common movie runtime in the 1990s?

• Which genres were most common during the decade?

• How many short Action movies were released?

• What trends could inform future investment decisions in nostalgic content?

## Dataset

**Source File**: netflix_data.csv

**Key Columns**

| Column       | Description           |
| ------------ | --------------------- |
| show_id      | Unique ID of the show |
| type         | Movie or TV Show      |
| title        | Title of the content  |
| director     | Director name         |
| cast         | Main cast members     |
| country      | Country of production |
| date_added   | Date added to Netflix |
| release_year | Year released         |
| rating       | Content rating        |
| duration     | Runtime in minutes    |
| listed_in    | Genre classification  |
| description  | Short summary         |


## Tools Used
• Python (pandas, matplotlib)
• Jupyter Notebook

## Analysis Workflow

**Data Preparation**

• Imported Netflix dataset into pandas

• Filtered for Movies only

• Selected movies released between 1990 and 1999

• Created duration analysis variables

• Identified short Action movies under 90 minutes

**Exploratory Analysis**

• Runtime distribution analysis

• Genre frequency analysis

• Histogram visualization of movie durations

• Bar chart of top genres in the 1990s

## Key Findings

**Most Common Movie Duration**

The most common movie duration for movies released in the 1990s was: **94 minutes**

This suggests that many films from the decade were designed around a concise, audience-friendly runtime.

**Short Action Movies**

The number of Action movies under 90 minutes was: **7 short Action movies**

This may indicate that shorter runtimes were less common in Action films, where longer storytelling and pacing were often preferred.

## Top Genres

The most common genres were:
• Action
• Drama
• Comedy

This suggests that high-energy entertainment, character-driven storytelling, and mainstream audience appeal dominated the decade.

## Visualizations

Distribution of Movie Durations

Histogram showing the spread of movie runtimes from 1990–1999.

## Top Genres by Number of Movies
Bar chart comparing the most common genres during the decade.
These visualizations help identify production trends and investment opportunities for nostalgic content.

## Business Insight
From an investment perspective, this project shows that:

• Mid-length films around 90–120 minutes were the standard

• Action, Drama, and Comedy had the strongest presence

• Nostalgic content from these genres may offer stronger audience familiarity

• Understanding historical patterns can support better modern content strategy decisions

This type of analysis can help streaming platforms, producers, and investors identify where audience preferences may still create strong returns.

## About Me
I’m Ryan Kelly, a Data Analytics student at Northeastern University interested in environmental systems, business analytics, and using data to support better decision-making.

## Connect
LinkedIn: https://www.linkedin.com/in/ryankelly10/
