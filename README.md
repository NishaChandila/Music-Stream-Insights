# Music Stream Analysis

> "Where words fail, music speaks."

# **INTRODUCTION**

As a data analyst, my objective was to transform raw music streaming data into meaningful insights that stakeholders can easily interpret and act upon. To achieve this, I began by cleaning and preparing the data using Python in Jupyter notebooks, applying various data wrangling techniques to ensure its quality and consistency. After the data was thoroughly cleaned and structured, I utilized Power BI to build an interactive dashboard that visualizes key metrics, trends, and performance across multiple platforms, including Spotify, YouTube, Apple Music, and more.

This dashboard provides a comprehensive view of music streaming activity, allowing stakeholders to explore different platforms, track performance over time, and make data-driven decisions. The final interactive report allows easy filtering by artist, track, platform, and year, ensuring that the analysis is both detailed and actionable.

- Music Stream [Data Cleaning & EDA](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/data-cleaning-and-eda-spotify.ipynb)
- Music Stream [Dataset](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/Most%20Streamed%20Spotify%20Songs%202024.csv)
- Music Stream [Power Bi Dashboard](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/Music-Stream-Dashboard.pdf)

# **DATA STRUCTURE**

The dataset used in this analysis contains detailed information about music streaming performance across various platforms. It includes metrics like playlist counts, streams, likes, and views from platforms such as Spotify, YouTube, TikTok, Apple Music, Pandora, and others. The dataset is essential for analyzing how music tracks perform over time and across different platforms, providing insights into top artists, tracks, and trends within the music industry.

![Dataset](https://github.com/NishaChandila/project-assets/blob/main/music-dataset.PNG)

## Column Descriptions:

- **AirPlay Spins**: The number of times a track has been played on AirPlay, a system used for streaming music across Apple devices.
- **Amazon Playlist Count**: The count of times a track has appeared on playlists within Amazon Music.
- **Apple Music Playlist Count**: The number of playlists a track has been included in on Apple Music.
- **Deezer Playlist Count**: The count of playlists a track has been featured on within Deezer, a global music streaming service.
- **Deezer Playlist Reach**: The total reach (number of users) of all playlists the track has appeared in on Deezer.
- **Explicit Track**: Indicates whether a track contains explicit content (1 for explicit, 0 for non-explicit).
- **ISRC**: The International Standard Recording Code, a unique identifier for each recorded music track.
- **Pandora Streams**: The number of times a track has been streamed on Pandora, an internet radio service.
- **Pandora Track Station**: The number of unique stations on Pandora that have played the track.
- **Release Date**: The official release date of the music track.
- **Shazam Counts**: The number of times a track has been identified through Shazam, a popular music recognition app.
- **SiriusXM Spins**: The number of times a track has been played on SiriusXM, a satellite radio service.
- **SoundCloud Streams**: The number of streams a track has accumulated on SoundCloud, a music sharing and streaming platform.
- **Spotify Playlist Count**: The number of playlists a track has been added to on Spotify.
- **Spotify Playlist Reach**: The total reach (number of users) of all Spotify playlists the track is a part of.
- **Spotify Popularity**: A metric that indicates how popular a track is on Spotify, calculated based on streams, playlist adds, and user interactions.
- **TikTok Likes**: The number of likes a track has received on TikTok, a short-video platform widely used for music discovery.
- **TikTok Posts**: The number of posts or videos on TikTok that feature the track.
- **TikTok Views**: The number of views a TikTok post featuring the track has received.
- **Track**: The name or title of the music track.
- **Track Score**: A calculated metric based on the track’s overall performance across platforms.
- **YouTube Likes**: The number of likes a track’s video has received on YouTube.
- **YouTube Playlist Reach**: The total reach (number of users) of all playlists the track has been added to on YouTube.
- **YouTube Views**: The number of views a track’s video has received on YouTube.

- Music Stream [Dataset](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/Most%20Streamed%20Spotify%20Songs%202024.csv)

# **EXECUTIVE SUMMARY**

This report analyzes the performance of music streaming across multiple platforms, offering valuable insights into key trends and metrics for artists, tracks, and platforms. The findings are presented through an interactive Power BI dashboard, which is divided into two main pages: Overview and Trends. Through data cleaning and preparation with Python (Jupyter), we ensured accurate and reliable insights to empower stakeholders in understanding the evolving landscape of music streaming.

![Home](https://github.com/NishaChandila/project-assets/blob/main/music1.PNG)

## **Overview Page:**
The Overview page presents key performance metrics for music streaming across major platforms, offering a snapshot of the top artists and their streaming performance.

![Overview](https://github.com/NishaChandila/project-assets/blob/main/music2.PNG)

- **Spotify Playlist Reach**: Taylor Swift leads with 2.2 billion in playlist reach, followed by Drake with 1.7 billion. These artists are among the top performers on Spotify.
- **YouTube Likes**: BTS has garnered the most likes on YouTube with 0.33 billion, while Blackpink follows closely with 0.25 billion likes.
- **Apple Music Playlist Count**: The top three artists by playlist count on Apple Music are:
  - The Weeknd: 31.37% of the total playlist count
  - Drake: 35.33%
  - Taylor Swift: 33.29%
- **Pandora Streams**: On Pandora, Drake is the top artist with 7.2 billion streams, followed by Maroon 5 with 5.8 billion streams.
- **TikTok Views**: Kevin MacLeod has the highest number of views with 0.23 trillion, while The King Khan follows closely with 0.21 trillion views.

These metrics provide a detailed picture of artist performance on different platforms, allowing stakeholders to see which artists and tracks are driving the most engagement and reach.

## **Trends Page:**
The Trends page provides a more detailed look at the performance of music streaming over time, highlighting peak periods and platform-specific trends.

![Trends](https://github.com/NishaChandila/project-assets/blob/main/music3.PNG)

- **Monthly Total Streams**: January saw the highest total streams at 0.52 trillion, with other peaks in May, October, and November (around 0.20 trillion streams). This shows strong seasonal patterns in music consumption.
- **Spotify Playlist Count by Year**: The number of Spotify playlists peaked in 2020 at approximately 30 million, indicating a surge in playlist creation and engagement during this period.
- **YouTube Playlist Reach by Year**: YouTube playlist reach reached its highest point in mid-2020, peaking just below 300 billion. This trend highlights the growth of video content engagement during this period.

These insights help identify significant trends in music streaming, such as seasonal spikes in streaming activity and shifts in platform usage over the years.

- Music Stream [Power Bi Dashboard](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/Music-Stream-Dashboard.pdf)

# **Data Cleaning & EDA**

We performed comprehensive data cleaning to ensure the accuracy and reliability of our analysis. This involved handling missing values, correcting inconsistencies, and removing irrelevant entries that could distort the results. To enhance the quality of our data, outliers were identified using statistical methods and visual tools like box plots. These outliers were carefully reviewed and removed when they were deemed irrelevant or erroneous for the purpose of our analysis.

- Missing values were handled through imputation or removal, depending on their significance.
- Inconsistent entries were corrected to standardize the data format.
- Outliers were identified using box plots and statistical thresholds to ensure that extreme values did not skew our results.
- Only valid and relevant data were retained, ensuring a robust and accurate dataset for the Power BI dashboard.

This thorough data cleaning process laid the foundation for the creation of our interactive Power BI dashboard, allowing stakeholders to make informed decisions based on clean and reliable data.

- Music Stream [Data Cleaning & EDA](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/data-cleaning-and-eda-spotify.ipynb)

## **Recommendation**

Based on the insights gathered, it's clear that music streaming trends are influenced by platform preferences and peak engagement periods. To optimize streaming strategies, stakeholders should consider the following key actions:

- **Promote Top Artists**: Focus on artists like **Taylor Swift** (2.2 billion on Spotify), **Drake** (1.7 billion on Spotify), and **BTS** (0.33 billion on YouTube), who dominate across multiple platforms.
  
- **Leverage Peak Months**: Align new releases with peak months like **January** (0.52 trillion streams) to drive higher engagement.
  
- **Tailor Content by Platform**: Customize strategies for **TikTok** (Kevin MacLeod leading with 0.23 trillion views), **Spotify**, and **YouTube** based on platform-specific trends.
  
- **Maximize Playlist Placement**: Prioritize getting tracks on popular playlists, especially on **Spotify** and **YouTube**, where playlist reach is significant.
  
- **Monitor Yearly Trends**: Keep track of evolving trends, especially the growth in playlist engagement (**Spotify** peaked in **2020** at 30 million playlists).
  
- **Target Regional Preferences**: Cater to regional music tastes based on platform popularity (e.g., **BTS** on YouTube).
  

# **CONCLUSION**

As a data analyst, I have carefully analyzed the streaming trends across multiple platforms, uncovering valuable insights into the performance of artists and their music. Our findings highlight top artists such as Taylor Swift, Drake, and BTS, along with peak streaming periods like January and 2020, particularly for Spotify and YouTube. Through thorough data cleaning and the removal of outliers, I ensured that the insights provided are both accurate and meaningful. This dashboard is designed to give stakeholders a clear understanding of current trends, allowing for informed decision-making and strategy development moving forward.

- Music Stream [Data Cleaning & EDA](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/data-cleaning-and-eda-spotify.ipynb)
- Music Stream [Dataset](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/Most%20Streamed%20Spotify%20Songs%202024.csv)
- Music Stream [Power Bi Dashboard](https://github.com/NishaChandila/Data-Cleaning-and-EDA-Spotify-/blob/main/Music-Stream-Dashboard.pdf)
