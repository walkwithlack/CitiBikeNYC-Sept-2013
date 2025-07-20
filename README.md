## NYC CitiBike Analysis — September 2013
This project explores trip-level data from New York City’s CitiBike program during September 2013, with a focus on uncovering user behavior patterns, trip durations, usage timing, and station activity.

## Project Goals
- Compare subscriber and non-subscriber usage

- Analyze trip durations and hourly usage trends

- Identify the most and least active start stations

- Visualize findings in Tableau

## Key Questions
- Who rides CitiBikes more frequently: subscribers or non-subscribers?

- How do trip durations differ between user types?

- What time of day is most active for each user group?

- Which start stations are most and least used?

## Contents
- data/: Original CSV trip data (available on Kaggle, see below under Data Source) and shapefile with neighborhood tabulation data from the Department of Planning of the NYC Government (see below under Data Source)

- notebooks/: Python notebooks for preprocessing and exploratory analysis

- tableau/: Tableau workbook (https://public.tableau.com/app/profile/magi.apostoli/viz/CitiBike_17530316678690/CitiBikeNYCSeptember2013)

- README.md: This file

## Data Source
This dataset contains trip-level rider information from the launch of Citi Bike through early October 2013. It was curated by Ryan Cummings and made publicly available via Kaggle (https://www.kaggle.com/datasets/ryanmcummings/citi-bike-data). The data captures individual rides taken using the Citi Bike bike-sharing system in New York City.
I sourced a shapefile from the Department of Planning of the NYC Government (nyc.gov/content/planning/pages/resources/datasets/neighborhood-tabulation) to create a choropleth map of NYC CitiBike trips. 

## Summary of Findings
- Subscribers are highly active during weekday rush hours, with shorter trips overall.

- Non-subscribers ride more randomly throughout the day and tend to take longer trips, often outside typical commuting windows.

- Top start stations align with busy hubs and workday commuting patterns.

- Least-used stations appear to reflect less frequent or irregular usage, possibly by tourists or in less central locations.

## Limitations

- Temporal Scope
The dataset includes only trips from September 1 to September 30, 2013, which limits analysis to a single month. This narrow time window prevents broader conclusions about seasonal, weekly, or year-over-year patterns.

- Sampling Size & Method
The dataset contains exactly 50,000 rows, which is likely a partial sample of all Citi Bike rides in September 2013. This suggests that the dataset is either a random sample or a truncated/arbitrary subset (e.g., the first 50,000 trips recorded). Because the sampling method is not documented, there is a risk of sampling bias, and the data may not fully represent all user behavior during the month.

## Next Steps
- Extend analysis across additional months or years for more robust trend insights.
  
- Incorporate weather or event data to understand external influences on ridership.
