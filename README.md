# Netflix Dataset Exploratory Data Analysis (EDA)

This project demonstrates EDA on the Netflix dataset using Apache Spark to uncover insights like content type distribution, production trends, top countries, and rating distribution.

## Requirements
- Python 3.8+
- Apache Spark 3.0+
- PySpark library

## Dataset
The dataset `netflix_titles.csv` contains:
- **type**: Movie or TV Show
- **release_year**: Year of release
- **country**: Country of production
- **rating**: Content rating (e.g., PG, R)

## Features
1. **Initialize Spark**: Creates a Spark session.
2. **Load Data**: Reads the dataset as a Spark DataFrame.
3. **Analysis**:
   - **Schema & Record Count**: Displays schema and record count.
   - **Content Type Distribution**: Movies vs. TV Shows.
   - **Yearly Trends**: Content production trends by year.
   - **Top Countries**: Top 10 content-producing countries.
   - **Ratings**: Distribution of content ratings.

## Usage
1. Place `netflix_titles.csv` in the project directory.
2. Install dependencies:
   ```bash
   pip install pyspark
   ```
3. Run the script:
   ```bash
   python netflix_eda.py
   ```



