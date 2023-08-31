# Data_Science

## Introduction
This project involves data analysis using various Python libraries, including Pandas, NumPy, Matplotlib, Seaborn, and WordCloud. The primary goal is to analyze a dataset containing information about Airbnb listings in New York City.

## Project Overview
The project is organized into several tasks, each focusing on a specific aspect of data analysis and visualization. Here's a brief overview of each task:

### Task 1: Data Cleaning
- The dataset is loaded from a CSV file named "AB_NYC_2019.csv."
- Rows containing invalid data are removed using the `dropna()` function in Pandas.
- Rows with price or availability equal to 0 are filtered out.

### Task 2: Neighborhood Analysis
#### Part A
- The top 5 and bottom 5 neighborhoods based on the price of Airbnb listings are determined.
- Data is filtered to include only neighborhoods with more than 5 listings.
- The mean prices of each neighborhood are calculated and ranked in descending order.

#### Part B
- A bar chart is created to visualize the average Airbnb listing price by neighborhood group (e.g., Manhattan, Brooklyn).
- Insights about price variations among different neighborhoods are discussed.

### Task 3: Correlation Analysis
- Correlation coefficients between various attributes (e.g., minimum nights, number of reviews, price) are computed and visualized using a heatmap.
- Positive and negative correlations are identified.

### Task 4: Geospatial Analysis
#### Part A
- A scatterplot is created to visualize the geographical distribution of Airbnb listings based on longitude and latitude.
- Data points are colored by neighborhood group to highlight spatial patterns.

#### Part B
- A scatterplot is generated to show the geographical distribution of Airbnb listings with prices less than or equal to $1000.
- Insights about the most expensive neighborhood group are discussed.

### Task 5: Word Cloud
- A word cloud is generated to visualize frequently occurring words in the "name" attribute of Airbnb listings.
- This provides insights into the common themes or descriptors used in listing names.

### Task 6: Host Analysis
- The busiest host in terms of the calculated host listings count is identified.
- Price and minimum nights are compared between the top 5 busiest hosts and all hosts.
- Insights about pricing and minimum-night requirements are discussed.

### Task 7: Room Type and Neighborhood Analysis
- A pie chart is created to visualize the distribution of room types in the Airbnb market.
- Insights about room type preferences are discussed.
- Another pie chart shows the distribution of Airbnb hosts across different neighborhoods in New York City.
- Insights about host distribution are provided.

## Dependencies
The project relies on several Python libraries, including:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

Make sure to install these libraries before running the code.

