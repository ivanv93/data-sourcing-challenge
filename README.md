# Data-Sourcing-Challenge

Welcome to my project on retrieving and cleaning movie data from The Movie Database (TMDB) and merging it with New York Times (NYT) movie reviews. The goal of this project was to create a comprehensive dataset that combines detailed movie information with professional reviews, to then be used for further analysis or exploration.

# Project Overview

In this project, I aimed to combine movie data from TMDB with movie reviews from NYT. By merging these two datasets, I was able to improve the data with details such as genres, spoken languages, and production countries, alongside critical reviews from NYT. The final dataset is cleaned and saved as a CSV file, ready for analysis. I was provided assistance by Sean Morey, the instructor of the class. I was provided amazing guidance from BCS tutors, Nomsa Tsotetsi and Angel Milla. I lastly could not have been able to finish this code without the help from the BCS Xpert Learning Assistant.

# Setup Steps

* Installed the necessary Python packages:

    - import requests
    - import time
    - from dotenv import load_dotenv
    - import os
    - import pandas as pd
    - import json

* Requested API keys from the New York Times and The Movie Database and saved them on a separate .env file for protection of my keys.

* I imported the API keys as variables, nyt_api_key and tmdb_api_key, to keep my keys secure and still request the data needed from both sources.