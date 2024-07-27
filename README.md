YouTube Analytics Project
Overview
This project involves analyzing YouTube video data by extracting user interaction metrics and performing sentiment analysis on video comments. The Python script provided in this repository fetches data for each video ID from a CSV file and processes it to provide various insights and analyses.

Features
The Python script performs the following tasks:

Data Extraction:

Downloads 100 comments for each video ID.
Extracts the video description, view count, like count, dislike count, comment count, video duration, and favorite count.
Ignores any video IDs that do not work and proceeds with the remaining ones.
Data Analysis:

Identifies the top-10 videos based on total views.
Identifies the bottom-10 videos based on total views.
Finds the most liked and least liked videos.
Determines the video with the highest duration.
Applies sentiment analysis on the downloaded comments and lists sentiment scores for each video.
