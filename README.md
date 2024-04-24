# Cyclistic-Bike-Share-Analysis
## About
This Python project aims to analyze the bike-share data of Cyclistic. The dataset includes ride data for all trips taken across the city of Chicago in 2023. It encompasses information such as start and end stations, start time and end time, member type, bike type, start coordinates, end coordinates, and the duration of time spent on bikes.

This project covers 
1. **Data cleaning and wrangling using pandas:** This step involves preparing the dataset for analysis by identifying and handling missing or inconsistent data, converting data types, and restructuring the data if needed. Pandas is a Python library commonly used for data manipulation and analysis, making tasks like data cleaning and wrangling efficient and straightforward.
2. **Data visualization using matplotlib, seaborn, and folium:** After cleaning the data, the next step is to visualize it to gain insights and identify patterns. Matplotlib and Seaborn are popular Python libraries for creating static, interactive, and customizable plots and graphs. They allow users to visualize relationships between variables, distributions of data, and trends over time. Folium, on the other hand, is a Python library used for visualizing geospatial data on interactive maps, making it suitable for plotting bike-share routes and station locations on a map.
3. **Route visualization using openrouteservices:** This step involves using the OpenRouteService API to visualize biking routes based on the data. OpenRouteService is a routing service that provides various APIs for calculating routes, isochrones, and matrix calculations. By leveraging this service, users can visualize biking routes between start and end stations, allowing for further analysis and insights into bike-share patterns.
4. **Reverse Geocoding using geopy:** Reverse geocoding is the process of converting geographic coordinates (latitude and longitude) into human-readable addresses. Geopy is a Python library that provides convenient access to several geocoding services, including reverse geocoding. By using geopy, users can retrieve addresses corresponding to the start and end coordinates of bike-share trips, enhancing the interpretation of route data and facilitating location-based analysis.

You can download the dataset [here](https://www.kaggle.com/datasets/liamkolanowski/cyclistic-cleaned-data/versions/1), and my Kaggle Notebook for this project [here](https://www.kaggle.com/code/rendangnoodle/cyclistic-bike-share).
