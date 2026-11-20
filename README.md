# Spotify Track Popularity Analysis (Power BI)

**By Jahmal Thurman**

## The Question
Does a song's sound, its energy and danceability, actually drive how popular it becomes? Or is popularity driven by something else?

## The Data
- 114,000 Spotify tracks (Kaggle dataset)
- 114 genres, 31,437 distinct artist credits
- Popularity scored 0 to 100; energy and danceability scored 0 to 1
- Tool: Microsoft Power BI (DAX, interactive visuals)

## Visual 1: Top Genres by Popularity
![Top genres by average popularity](Screenshot%202026-11-20%20180313.png)

The top 15 genres ranked by average popularity. Pop-film, K-pop, and chill lead, showing where broad listener attention already sits.

## Visual 2: Hits vs Rest Sound Profile
![Hits vs Rest sound profile](Screenshot%202026-11-20%20180250.png)

Tracks split into Hits (popularity 70 or higher) versus everything else, compared on average energy and danceability.

## The Finding
Hit songs are only about 3 points more energetic and 6 points more danceable than everything else, on a 100-point scale. The difference is real but small.

## What It Means
Sound leans in the right direction, but the gap is too small to be the real driver of a hit. What actually separates a hit is likely outside the audio: artist reach, playlist placement, and marketing. A label or marketer should not chase a "more danceable sound" expecting hits. The money is better spent on reach and promotion.

## Built With
- Power BI Desktop
- A DAX calculated column to classify each track as Hit or Rest
- Source file: Spotify_powerBI_Analysis.pbix (download to open in Power BI)

## Part of a Series
Same dataset, analyzed three ways:
- SQL: github.com/jahmalthurman-analytics/spotify-track-analysis
