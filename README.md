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
