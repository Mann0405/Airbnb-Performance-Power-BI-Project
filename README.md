# Airbnb-Performance-Power-BI-Project

## Project Objective

A dynamic, interactive data visualization tool built to provide a comprehensive analysis of Airbnb's global performance across a selected set of global cities. It examines listings, reviews, ratings, seasonality, and trust metrics to identify market trends, compare city performance, and uncover insights into customer and host behavior.

## Tech Stack

The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

## Data Source
- <a href="https://mavenanalytics.io/data-playground/airbnb-listings-reviews>Airbnb Dataset</a>

## Features

### 1. Business Problem - Airbnb operates across multiple cities and property types, making it challenging to understand how market performance, customer satisfaction, review activity, and host trust vary across locations, and to identify growth opportunities, monitor customer experience, and make data-driven decisions.
Key questions such as:
Which cities contribute the largest share of Airbnb listings? How frequently do customers leave reviews? What proportion of hosts have verified profiles? How has Airbnb's listing growth changed over time?… are difficult to answer quickly with raw data.

### 2. Goal of the Dashboard
To deliver an interactive visual tool that:
Enables users to explore Airbnb performance across selected cities through listings, ratings, reviews, and host metrics.
Supports data-driven decisions related to customer experience, market performance, and platform growth.
Uncovers trends in customer satisfaction, review behavior, property distribution, and host trust indicators.

### 3. Walkthrough of Key Visuals
#### Overview Page
- KPI Cards (Top Section)
279,712 Listings: Total number of Airbnb properties listed across the selected cities.
10 Cities: Number of cities included in the analysis.
182,024 Hosts: Total hosts managing Airbnb properties.
144 Property Types: Variety of accommodation types offered on the platform.
5.373K Reviews: Total customer reviews captured in the dataset.

- New Listings Trend Analysis (Main Visual): A line chart that shows how Airbnb listings evolved from 2008–2021 for different room types.

#### Ratings Page
- Market Share by City: An interactive line and stacked column chart that compares the number of Airbnb listings across the selected cities with the distribution between Superhost and Non-Superhost Listings, and shows their cumulative contribution.

- Average Price by Room Type: An interactive horizontal bar chart that compares the average price of different room types.

- Rating Navigation Panel: It uses Power BI bookmarks to provide an interactive navigation experience to allow users to switch between Overall Rating and Detailed Rating views.
  
- Overall Rating by City: A column chart that compares the average overall Airbnb rating across cities.

- Detailed Ratings Analysis Heatmap: A table that compares city ratings across five customer satisfaction dimensions: Accuracy, Cleanliness, Communication, Location, Value

#### Reviews Page
- Review Frequency (Pareto Chart): Combines review counts with cumulative percentages to identify how review activity is distributed among customers.

- Seasonality Analysis: A ribbon chart is used to show how review activity is distributed throughout the year across cities.

- Trust Analysis: This visual evaluates host trustworthiness using two key trust signals: Identity Verification and Profile Picture Availability.

### 4. Key Insights
- Airbnb experienced strong growth until 2015, highlighting the platform's rapid expansion before entering a more mature phase.
- Entire Place listings dominate the market, indicating a strong preference for private accommodations and a key revenue opportunity.
- Paris is the city with the most listings and reviews. A possible driver is the prices for hotel rooms being twice as much as Airbnb!
- Paris, New York City, and Sydney account for nearly half of all listings and reviews, making them critical markets for growth and engagement.
- Non-Superhosts contribute the majority of listings, suggesting an opportunity to increase the number of Superhosts and improve service quality.
- Mexico City and Rio de Janeiro achieve the highest customer satisfaction ratings, providing benchmarks for improving guest experiences in other cities.
- Most customers leave only one review, showing that repeat review activity is limited.
- Paris and Rome dominate review share from April to August, reflecting peak European summer travel. New York saw an increase in November and December during the holiday season.
- Over 99% of hosts provide at least one trust indicator (identity verification or profile picture), helping build guest confidence in the platform.
- The COVID-19 period caused a significant decline in listing growth, demonstrating the platform's sensitivity to global travel disruptions.

- Identify high-demand markets for targeted growth and marketing strategies.
- Improve host performance by focusing on cleanliness, value, and customer experience.
- Use seasonal trends to optimize pricing and promotional campaigns.
- Strengthen host trust programs to enhance guest confidence and platform reliability.
- Leverage insights from highly rated cities to improve performance in other markets.

## Dashboard
