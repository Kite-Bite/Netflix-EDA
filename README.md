# Netflix Movies & TV Shows: Exploratory Data Analysis

A simple EDA on the Netflix titles dataset, exploring content type, growth over time, countries, genres, ratings, durations, and directors.

## Dataset

The notebook reads `netflix_titles.csv`.

## What's inside

`netflix_eda.ipynb` walks through:

- **Data overview**: shape, dtypes, null values, duplicates for Movies vs TV Shows
- **Data cleaning**: filling missing `director`/`cast`/`country`, dropping rows with missing `rating`, parsing `date_added`, engineering a `year_added` column
- **Visual analysis**:
  1. Movies vs TV Shows split
  2. Content added to Netflix over the years
  3. Top 10 content-producing countries
  4. Most common genres
  5. Content rating distribution
  6. Movie duration distribution
  7. TV show seasons distribution
  8. Release year trend
  9. Most frequent directors
- **Key insights** summarizing the findings

## Requirements

```
pandas
numpy
matplotlib
seaborn
```

Install with:

```bash
pip install pandas numpy matplotlib seaborn
```

## Running

```bash
jupyter notebook netflix_eda.ipynb
```

## Key Insights

- Movies make up roughly 70% of the catalog, TV shows about 30%.
- The catalog grew rapidly between 2015–2019, slowing after 2020.
- The US and India are the top content-producing countries, followed by the UK.
- International Movies, Dramas, and Comedies are the most common genres.
- TV-MA and TV-14 are the most common ratings — the catalog leans toward mature/teen audiences.
- Most movies run 80–120 minutes; most TV shows have just one season.
- Content skews toward recent release years rather than older titles.
