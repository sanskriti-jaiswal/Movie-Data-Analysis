# Movie Dataset Analysis Project

## Overview
This project analyzes a movie dataset (`mymoviedb.csv`) to extract insights about genre popularity, movie ratings, and release trends. The analysis explores patterns in movie popularity, vote averages, and release dates across different genres.

## Repository Contents
- `movie-data-analysis.ipynb`: Jupyter notebook containing all the analysis code and visualizations
- `mymoviedb.csv`: The dataset containing movie information

## Dataset
The dataset contains information about movies including:
- Release Date
- Title
- Popularity scores
- Vote Count
- Vote Average
- Genre
- Poster URL

## Key Findings

### Genre Analysis
- **Most Frequent Genre**: Drama is the most frequent genre, appearing in more than 14% of the movies among 19 other genres.
- **Highest Voted Genre**: Drama also receives the highest popularity among fans, accounting for more than 18.5% of popular movies (25.5% of the dataset has 'popular' vote ratings).

### Movie Popularity
- **Highest Popularity**: "Spider-Man: No Way Home" has the highest popularity rating (Action, Adventure, Science Fiction).
- **Lowest Popularity**: "The United States, Thread" has the lowest popularity rating (Music, Drama, War, Sci-Fi, History).

### Release Date Analysis
- **Peak Production Year**: 2020 has the highest film production rate in the dataset.

## Methodology
The analysis involved:
1. Data cleaning and preprocessing (removing missing values)
2. Genre extraction and normalization (exploding multiple genres per movie)
3. Categorization of numerical columns (like Vote_Average)
4. Statistical analysis and visualization using Seaborn

## Visualizations
The project includes multiple visualizations:
- Genre distribution count plot
- Vote average category distribution
- Release date histogram

## Technical Details
- **Programming Language**: Python
- **Key Libraries**: 
  - pandas (data manipulation)
  - Seaborn/Matplotlib (visualization)
- **Data Transformations**:
  - Conversion of Release_Date to year format
  - Splitting and exploding of genre data
  - Categorization of Vote_Average into meaningful groups

## How to Run
1. Ensure Python and required libraries are installed
2. Clone the repository
3. Open and run the Jupyter notebook
```
pip install pandas matplotlib seaborn jupyter
jupyter notebook movie-data-analysis.ipynb
```

## Future Work
- Time series analysis of popularity trends by year
- Sentiment analysis of movie titles

---

