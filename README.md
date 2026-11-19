# TwitchStreamer
My app helps Twitch and YouTube creators decide which Steam game to stream next by ranking games based on concurrent players, average playtime, release date, and player ratings.

# StreamPick – Steam Game Discovery for Streamers

My app helps Twitch and YouTube content creators decide which Steam game to stream next by analyzing player popularity, average playtime, and player ratings to identify potentially promising games.

> A course project for **MIST 4600: Computer Programming in Business** at the University of Georgia's Terry College of Business (Fall 2026).

## Problem

Twitch and YouTube content creators must constantly decide which games to play to attract and maintain an audience. Choosing a game can be difficult because popular games may have significant competition from other streamers, while less popular games may have limited audience interest. StreamPick analyzes Steam game data to help creators identify games with strong player interest, engagement, and ratings.

## What it does

My app answers three questions:

1. **Popularity:** Which Steam games have the highest peak concurrent player counts?
2. **Engagement:** Which games have the highest average playtime per owner?
3. **Recommendation:** Which games combine strong player ratings with high concurrent player counts?

StreamPick uses these results to generate a shortlist of games that may be worth considering for a Twitch or YouTube stream.

The project may also incorporate live Twitch streaming data to compare viewer counts and the number of channels streaming each game.

## Data

The [Steam Games Dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) on Kaggle, collected in March 2025. The dataset is shared under the MIT License by its creator, artermiloff.

This repository uses `steam_games.csv`, a smaller file made for the course: the 1,000 games with the most reviews.

The project uses the following dataset columns:

- `name`: Game title
- `peak_ccu`: Peak concurrent Steam players
- `avg_playtime_hours`: Average playtime per owner
- `pct_pos_total`: Percentage of positive player reviews
- `num_reviews_total`: Total number of player reviews
- `release_date`: Game release date

**Data limitation:** Steam player counts represent a March 2025 snapshot and do not necessarily reflect current player activity. Steam concurrent players also do not directly measure Twitch or YouTube viewership.

## Built with

- **Python:** Main programming language
- **pandas:** Data cleaning, filtering, and analysis
- **Google Colab:** Development environment
- **GitHub:** Version control and project publishing
- **Twitch Helix API (planned):** Retrieving live streaming and viewer information
- **Matplotlib (planned):** Data visualization

## How to run it

Coming soon.

Planned steps:

1. Download or clone this repository.
2. Make sure Python is installed.
3. Install the required Python packages.
4. Place `steam_games.csv` in the project directory.
5. Run the Python application.

## Example output

Coming soon.

The application will display:

- The most popular Steam games based on peak concurrent players.
- Games with the highest average playtime.
- Recommended games based on player ratings and popularity.
- Potentially, live Twitch viewer and channel statistics.

## AI Use Disclosure

AI tools, including ChatGPT, may be used to assist with brainstorming, understanding Python concepts, debugging, and improving project documentation.

All submitted code will be reviewed and tested by the author to ensure an understanding of the program's functionality. AI assistance will be disclosed in accordance with the course requirements.

## Author

Justin Rather

University of Georgia  
Terry College of Business  
MIST 4600 – Fall 2026
