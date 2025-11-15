Real Estate Market Insights – Zameen.com EDA Project

This project presents an exploratory data analysis (EDA) of residential property listings scraped from Zameen.com, one of Pakistan’s largest real estate platforms. The goal is to understand pricing behaviour, location-based trends, property characteristics, and the factors that influence market value across major and secondary cities.

Project Objectives

Analyse price distributions and market segmentation

Compare listing volumes across cities and property types

Examine how structural features (area, bedrooms, bathrooms) relate to price

Identify trends across top 10 cities

Compute correlations to understand key drivers of price

Present clean visual insights for investors, analysts, and researchers

Dataset

The dataset contains thousands of residential property listings from Zameen.com, including:

City and Location

Property Type

Area (converted to sqft)

Price

Bedrooms and Bathrooms

Description

Derived features (Price_per_sqft, Area_sqft, City Category)

All data cleaning, preprocessing, and feature engineering steps are documented in the notebook.

Data Cleaning and Preparation

Key preprocessing steps include:

Removing PKR symbols, commas, and extra text from price

Converting area units (Marla, Kanal, Sq. Yard) to square feet

Standardizing property types and city names

Handling missing values and invalid zeros

Recalculating Price_per_sqft using cleaned columns

Removing outliers and extreme distortions

Applying log transformations for skewed variables

Visualisations Included

The analysis includes the following plots:

Price Distribution (Log Scale)

Distribution of Property Types

Top 10 Cities by Listing Volume

Price by Property Type (Boxplot)

Price Distribution Across Top Cities (Log Boxplot)

Area vs Price (Scatterplot with Log Transformation)

Price by Number of Bedrooms

Correlation Heatmap (Cleaned Data)

Each visual is accompanied by a structured explanation that captures key trends.

Key Insights

The market is segmented into mid-range and luxury price clusters.

Houses dominate the listing volume, followed by flats.

Karachi, Islamabad, and Lahore represent the most active and high-value markets.

Area and structural features influence price, but location remains a major driver.

Smaller properties often have higher price-per-square-foot values.

Price increases consistently with higher bedroom counts, especially beyond four bedrooms.

Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook or Google Colab

How to Run the Notebook

Clone the repository

Install the required libraries

Open the notebook in Jupyter or Colab

Run all cells in sequence to reproduce the analysis
