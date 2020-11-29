# Cross-european analysis of Spotify song preferences using Spotifyr 
Final project for Cultural Data Science

# Project description
Goal: 
With this project we tried to assess whether we could detect stereotypes of Northern vs. Southern europeans objectively through their preferences for music.

Background: 
In a European context, we often see the temper of Northern Europeans being stereotyped as reserved and "cold". In contrast, the temper of Southerners is described as passionate and "warm". But are these stereotypes objectively measurable?

Scope: 
With this analysis we tried to test the stereotypes by looking at the current "Top 50 Music Charts" on Spotify with playlists from 38 European countries. 

# Method: 
The entire analysis was conducted in the open source analysis software tool R Studio (RStudio Team (2019)).

We used Spotify's open source web API to access user data: https://developer.spotify.com/documentation/web-api/

We used the R-package "Spotifyr" to scrape our profiles: https://github.com/charlie86/spotifyr#overview

We used the R-package "Highcharter" to create interactive plots for visual assessment: 

# Acknowledgement:
This repo is largly build on the analysis  by Paul Elver (Copyright (c) 2018 paulelvers): https://github.com/paulelvers/sentiment_analysis/blob/master/sentiment_music_project.R

# How to use:
"Top_charts_script.Rmd": This markdown file contains the entire code used for the analysis

"Top_charts_script.html": This html file contains the code and output for the analysis

"Data" Folder: This folder contains all the written .csv files used for the analysis

"Figures" Folder: This folder contains all the figures created in the analysis

"Final_project_writeup.pdf": This pdf file contains the written report of the analysis as handed in by the exam deadline (4th Jan. 2021)
