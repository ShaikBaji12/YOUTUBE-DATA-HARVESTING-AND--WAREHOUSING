# YOUTUBE-DATA-HARVESTING-AND--WAREHOUSING
Project Overview:

This project aims to create a user-friendly Streamlit application for accessing and analyzing data from multiple YouTube channels.

Key Features:

YouTube Data Retrieval: Users can enter a YouTube channel ID and retrieve essential data such as channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments using the Google API.

Data Storage: The application allows storing retrieved data in MongoDB, providing a flexible data lake. Users can collect data from up to 10 YouTube channels and store them with a single click.

Data Migration: Users can select a channel name and migrate its data from MongoDB to a SQL database for structured storage and analysis.

Querying SQL Data: Users can search and retrieve data from the SQL database, including joining tables for comprehensive channel details.

Integration: The application seamlessly integrates with the YouTube API, MongoDB, and SQL databases.

Technologies Used:

Python (libraries like googleapiclient, pymongo, pymysql, pandas)
Streamlit
MongoDB
SQL Database (e.g., MySQL, PostgreSQL)
Google API client library for Python
Conclusion:

This project simplifies the process of accessing and analyzing YouTube channel data through an Streamlit interface. Users can effortlessly retrieve, store, and query data, enabling insightful analysis with minimal effort.

Usage:

1.Launch the Streamlit app: streamlit run baji.py

2.The app will start and open in your browser. You can explore the harvested YouTube data and visualize the results.
