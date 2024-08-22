# Festival Lineup Guide: Tomorrowland Belgium W2 2024

## Overview

This project aims to help festival goers plan their schedule for Tomorrowland Belgium Weekend 2 by providing an interactive dashboard that allows users to filter and view artist information. The project extracts festival lineup data, enriches it with Spotify artist data, and presents it through a Dash-based web application.

## Project Outline

1. **Read Data**
   - Extract stage, host, artist, and day information from an Excel file containing Tomorrowland Belgium Weekend 2 lineup data.

2. **API Integration**
   - Use the Spotipy library to get additional information for each artist, including popularity, top 3 songs, and genre from the Spotify API.

3. **Dashboard**
   - Create an interactive dashboard using Dash that allows users to filter by day, stage, and popularity.
   - Display artist information that matches the selected filters.


# Oliver Heldens vs Hi-Lo: Top Tracks, Followers & Popularity Comparison

This project uses the Spotify API to analyze and compare the top tracks, popularity, and follower counts of the artist Oliver Heldens under his two aliases: **Oliver Heldens** and **Hi-Lo**. The project involves retrieving data via the Spotify API, organizing it into DataFrames, and visualizing the results using Seaborn and Matplotlib.

## Project Overview

The project performs the following key tasks:
1. **Data Retrieval**: Fetches top tracks, popularity, and follower data for both Oliver Heldens and Hi-Lo using the Spotify API.
2. **Data Processing**: Organizes the retrieved data into Pandas DataFrames for analysis.
3. **Visualization**: Creates comparative visualizations to explore the popularity and followers of the two aliases.

## Features

- **Comparison of Top Tracks**: Displays a bar chart comparing the popularity of top tracks for both aliases.
- **Follower Count Comparison**: Visualizes the difference in follower counts between the two aliases.
- **Popularity Comparison**: Compares the overall popularity of the aliases.


# Eric Prydz vs Pryda: Top Tracks Comparison

This project compares the top tracks of two aliases of the artist Eric Prydz: **Pryda** and **Eric Prydz.** The comparison is done by retrieving the top tracks for each alias using the Spotify Web API, storing track information in DataFrames, and visualizing the data using a bar chart.

## Project Overview

This script uses the [Spotipy](https://spotipy.readthedocs.io/en/2.19.0/) library to interact with the Spotify Web API. It retrieves and compares the top tracks of two aliases for Eric Prydz:
- Pryda
- Eric Prydz

The comparison is visualized in a bar chart showing the popularity of tracks from both aliases.
