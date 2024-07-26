# Movie Sourcing Using NYT & TMDB API
![Logo for assignment of movie related images](logo.gif)
# 🗺️ Overview
This is by far the most fun I have had thus far in my Bootcamp experience. This program was designed to test everything we have learned up to this point, by using data extracted from the New York Times and The Movie Database API's. This program channels movie titles retrieved from the New York Times API into The Movie Database API to pull the associate movies details for each movie. 

Ultimately we made two dataframe out the information retrieved from both endpoints and combined them into one dataframe. Once combined, we were tasked with cleaning the data and exporting a clean version of the combined data. 
## ✐ Description
Creates clean visualizaton for analyzing movie data using movie titles from the NYT API to search for additional information on the TMDB database. 
## 📉 Installation 
1. Clone Repository: `git clone https://github.com/ncmoliver/data-sourcing-challenge.git`
2. Navigate to project repository
3. Install required dependencies
request | `pip install requests`
pandas | `pip install pandas`
dotenv | `pip install dotenv`
json | `pip install json`
os | `pip install os`
time | `pip install time`

## ⚙️ How It Works
1. Open the `retrieve_movie_data.ipynb` Jupyter Notebook.
2. Run the notebook cells sequentially to execute the data retrieval process.
3. The script will fetch movies from the New York Times API and use the titles to fetch addtional details on each movie through TMDB API.
4. Using the data retrieved, the program will combine the dataframes into one dataframe (on the 'title' column) and clean it up for readability.
## Key Functions
| Function | Description |
| ----------- | ----------- |
| Loading Environment Variables | Constructs the query URL with the required parameters and filters. |
| Fetching Data | Sends requests to the NYT API requests to retrieve movie review information and aggregates them. |
| Rate Limiting | Implements a delay between API request to comply with rate limits.ext |
## References
[Xpert Learning Assistance](https://bootcampspot.instructure.com/courses/6028/external_tools/313)    
[Slack BCS Learning Assistant](https://slack.com)
[Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/)
[New York Times API](https://developer.nytimes.com/docs/movie-reviews-api/1/overview)
[The Movie Database API](https://developer.themoviedb.org/reference/intro/getting-started)