# Zomato Food Trends - Power BI Analysis

# Project Overview
Zomato Food Trends is a Power BI project designed to analyze global restaurant data using Zomato’s dataset. This report provides deep insights into restaurant distribution, public ratings, feedback, and revenue across various countries and cities. By leveraging powerful data visualization techniques, the report helps uncover dining trends, customer preferences, and business performance in the restaurant industry.

# Key Features :

# Slicers
Country: Filter restaurants based on specific countries to narrow down the analysis.
Price Range: Adjust the price range to explore how different pricing tiers affect key metrics.

# Cards
Average Counts: Displays average metrics for selected data (such as average ratings, costs, etc.).
Total Votes: Summarizes the total number of customer votes and feedback.
Average Cost: Shows the average cost per restaurant across selected filters.
Total Restaurants: Highlights the total number of restaurants in the dataset.
Total City Counts: Displays the total number of cities included in the analysis.

# Visual Charts
Cuisines by Cities (Tree Map): Represents the variety of cuisines offered in different cities through a visually appealing tree map.
World Map: Displays the global distribution of restaurants and their respective metrics on an interactive map.
Top 10 Cities by Ratings (Pie Chart): Highlights the cities with the highest average restaurant ratings.
Restaurants by Ratings (Bar Chart): Visualizes the number of restaurants in different rating categories using a bar chart.
Text Voting Analysis (Clustered Bar Charts): Analyzes customer feedback and voting patterns by visualizing text data with clustered bar charts.
Data Preparation and Transformation

# In this project, Power Query was extensively used for data transformation to ensure clean, structured, and insightful data:
Data Transformation: Applied various cleaning and transformation steps to optimize the raw Zomato dataset for analysis.
Split Function: Utilized the split function to break down complex fields, such as separating city and country data, or extracting specific components from text fields.
Merge Function: Merged multiple columns where necessary, such as combining address-related fields into a single column.
Unpivoting Columns: Transformed certain pivoted columns (e.g., restaurant metrics) back into a normalized format for easier analysis.
DAX Formulas and Calculations

# DAX (Data Analysis Expressions) was employed to create new calculated fields and perform dynamic data analysis:
New Columns: Added calculated columns to derive insights like rating-to-price ratios, revenue per restaurant, and more.
DAX Measures: Created custom DAX measures for calculating complex metrics, such as weighted averages, cumulative totals, and comparative analysis over time.
Some of the custom DAX formulas used include:
Total Revenue: SUM(Revenue), giving a total count of the revenue for selected filters.
Average Rating: AVERAGE(Rating), to dynamically calculate the average restaurant rating across different filters.
Top 10 Cities by Ratings: Calculated a dynamic measure to rank cities based on average ratings.

# How to Use
Slicers: Interact with slicers to filter data by country or price range.
Cards: Review quick metrics like average counts, total votes, and the number of restaurants and cities.
Visuals: Explore the variety of visual charts to analyze the data from different perspectives.
Data Transformation: Examine how the dataset has been cleaned, transformed, and optimized for efficient data analysis.
DAX Insights: Take advantage of DAX-driven calculations for deeper insights into restaurant performance and trends.
Tools & Technologies
Power BI: For creating data visualizations and dashboard reporting.
Power Query: For data transformation and cleansing.
DAX (Data Analysis Expressions): For creating calculated fields, measures, and advanced analytics.
Requirements
