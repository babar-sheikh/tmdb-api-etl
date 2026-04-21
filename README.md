# TMDB Top Rated Movies Scraper

This project is a Python-based data collection tool that extracts information about the highest-rated movies from **The Movie Database (TMDB) API**. It automates the process of paginating through the API to build a comprehensive dataset of over 8,500 movies.

## 📊 Dataset Overview
The final output (`moives.csv`) contains the following features:
* `id`: Unique identifier for each movie.
* `title`: The official title of the movie.
* `overview`: A brief summary or plot description.
* `popularity`: TMDB's internal popularity score.
* `release_date`: The date the movie was first released.
* `vote_average`: The average user rating (out of 10).
* `vote_count`: Total number of user votes.

## How It Works
The project uses the `requests` library to loop through ~428 pages of the TMDB API. The data is then parsed, cleaned, and organized into a `pandas` DataFrame before being exported.

### Prerequisites
To run the notebook, you will need:
* Python 3.x
* Pandas
* Requests
* A TMDB API Key (you can get one at [developers.themoviedb.org](https://developers.themoviedb.org/))

### Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/tmdb-top-rated.git](https://github.com/your-username/tmdb-top-rated.git)
