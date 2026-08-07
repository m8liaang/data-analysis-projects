# Netflix Exploratory Data Analysis Project
An exploratory data analysis project on movies and TV shows on Netflix. Three CSV files describing one dataset were processed, and certain areas of interest were identified and analyzed. The dataset used for this analysis contained Netflix movies and TV shows that were released from 1940 to 2017, and included information on their maturity ratings, rating scores, 

## Data Sources
Data is from [data.world and Chase Willden](https://data.world/chasewillden/netflix-shows).

The dataset was accessed via the [DataCamp community-groupby repository](https://github.com/datacamp/community-groupby/tree/master/data).

The DataCamp repository served as a convenient source for the CSV files, while the original dataset is hosted on data.world.

## Toolkit/Python Libraries Used
Pandas, matplotlib, seaborn

## Analysis Performed
- Data cleaning and restructuring
- Data visualization
- Data analysis

## Assumptions
The dataset did not give information as to what some of the columns meant. One such column, titled "rating description", was assumed to be the rating score critics gave the particular movie or TV show. The number of critics that contributed to this score was also unknown; therefore, it is possible that way more critics rated certain movies and TV shows compared to Netflix users. As a result, it was assumed that the two groups were similar in size.

Certain maturity ratings (NR and UR, "Not Rated" and "Unrated" respectively) may include both movies and TV shows, which would affect calculating the average rating scores of critics and users alike. NR and UR were, therefore, not included in this data analysis.

## Key Findings
1. 
2. 
3. 

## Limitations
Sample size was not known for critic rating scores. A much larger sample size could cause the average rating score to be way higher or lower than it really is. Not including UR and NR ratings in the analysis would also affect the average user and critics rating scores.

The dataset also does not have an equal number of movies and TV shows released every year from 1940 to 2017. More movies and/or TV shows being released in one year (e.g. 2016) could skew the average rating score for that year for both users and critics, as the sample size would be much larger.

## Project Structure
```text
netflix_eda_project/
├── netflix_eda.ipynb
├── README.md
```
