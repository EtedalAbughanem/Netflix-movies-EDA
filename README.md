# Netflix-movies-EDA
Exploratory analysis of 1990s Netflix movies, including the most common duration and the count of short action movies.

## Project Overview

This project involves exploratory data analysis (EDA) on a dataset of Netflix movies, focusing on those released in the 1990s. The analysis aims to:

1. Determine the most frequent movie duration during the 1990s.
2. Count the number of short action movies (less than 90 minutes) released in the 1990s.

## Dataset

The dataset used for this analysis is `netflix_data.csv` and includes the following columns:

- `show_id`: The ID of the show
- `type`: Type of show
- `title`: Title of the show
- `director`: Director of the show
- `cast`: Cast of the show
- `country`: Country of origin
- `date_added`: Date added to Netflix
- `release_year`: Year of Netflix release
- `duration`: Duration of the show in minutes
- `description`: Description of the show
- `genre`: Show genre

## Analysis

1. **Most Frequent Movie Duration in the 1990s:**
   - Filter movies released in the 1990s.
   - Plot the distribution of movie durations.
   - Compute the most frequent movie duration.

2. **Count of Short Action Movies in the 1990s:**
   - Filter for action movies from the 1990s.
   - Count how many of these movies have a duration of less than 90 minutes.

## Results

- **Most Frequent Movie Duration:**
  The most frequent duration of movies from the 1990s is `duration` minutes.

- **Number of Short Action Movies:**
  The number of short action movies (less than 90 minutes) from the 1990s is `short_movie_count`.

## Usage

To replicate the analysis, follow these steps:

1. Ensure you have the necessary libraries installed (`pandas` and `matplotlib`).
2. Run the provided Python script to load the dataset, filter the data, and compute the required metrics.
3. Review the histogram and printed results for insights.

## Dependencies

- pandas
- matplotlib
