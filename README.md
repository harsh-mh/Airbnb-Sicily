# Airbnb Big Data Analytics: Sicily, Italy

## Overview

This project analyzes Airbnb data for Sicily, Italy, to provide insights into pricing trends, booking behavior, and other factors relevant to the local market. The analysis uses a variety of techniques, including data cleaning, transformation, and visualization, to answer key business questions.

## Team

* Sameer Afzal
* Harsh Mehta
* Asad Aslam [cite: 13]

## Project Structure

The repository contains the following main components:

* **Data:** Contains the datasets used in the analysis.
* **ETL:** Includes scripts or documentation detailing the Extract, Transform, Load process.
* **Dashboards:** Tableau dashboards visualizing the analysis results.
* **Documentation:** Project reports and supporting documents.

## Datasets

The analysis is based on the Inside Airbnb dataset for the Sicily region. [cite: 23, 24] The following tables were used:

* Listing
* Calendar
* Reviews
* Neighborhood

## Business Questions

The analysis seeks to answer the following business questions:

1.  How does the average price & count of review differ for different room types within a specific city? [cite: 25]
2.  What is the distribution of room type in different cities with respect to average price & reviews? [cite: 26]
3.  Which month experiences the highest demand booked listing for each room type? [cite: 27]
4.  What are the seasonal trends in booking behavior? [cite: 27]
5.  Where do one or a few cities dominate the market in terms of listing percentage? [cite: 28]
6.  What is the trend in the number of reviews over the past 10 years and how has it been impacted by the COVID-19 pandemic? [cite: 29]

## ETL Process

The ETL process involved the following steps:

1.  **Extraction:** Data was extracted from the Inside Airbnb website. [cite: 38, 39]
2.  **Cleansing:** Data was cleaned to handle inconsistencies, errors, and missing values. [cite: 38, 39, 40, 41]
3.  **Transformation:** Data was transformed into a suitable format for analysis. [cite: 38, 42, 43]
4.  **Loading:** Data was loaded into Tableau for analysis and visualization. [cite: 38, 42, 43, 44]

   Tableau Prep Builder was used for cleaning, transformation, and loading the data. [cite: 44, 45]

   Key data cleaning steps included:

    * Removing unnecessary columns (e.g., auto-generated row numbers, neighborhood group, and license column). [cite: 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57]
    * Handling missing values (e.g., replacing empty BNB names and host names with "Unspecified," replacing null review counts with 0). [cite: 53]
    * Rounding off numerical values. [cite: 54]
    * Sampling large datasets to improve processing efficiency. [cite: 56, 57, 58, 59]

## Dashboards

The project includes interactive dashboards to visualize key findings:

* **Main Dashboard:** Provides a high-level overview of listings, hosts, reviews, and pricing. [cite: 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75]
* **Price – Host – City Analysis Dashboard:** Explores the relationship between price, hosts, and cities. [cite: 76, 77, 78, 79, 80, 81, 82, 83, 84, 85, 86]
* **Room Type Analysis Dashboard:** Analyzes different room types and their characteristics. [cite: 87, 88, 89, 90, 91, 92, 93, 94, 95, 96]
* **Timelines Dashboard:** Visualizes revenue from advanced bookings and booking trends over time. [cite: 97, 98, 99, 100, 101, 102, 103]
* **Listings in Sicily Dashboard:** Shows the distribution of listings across different cities in Sicily. [cite: 104, 105, 106, 107, 108, 109, 110, 111, 112]

## Key Findings

* Catania has cheaper hotel and private rooms compared to the average price in the rest of Sicily. [cite: 113, 114]
* Palermo, Syracuse, and Catania have the highest number of listings. [cite: 107]
* Palermo has the largest number of listings across all room types. [cite: 115, 116, 117]
* April has the highest number of advanced bookings, followed by August and July. [cite: 118]
* August has the highest average price for accommodations. [cite: 119, 120, 121]
* There's a discrepancy between visitor numbers and bookings. Taormina has the highest number of visitors, but cities like Palermo, Syracuse, and Catania have the highest number of bookings. [cite: 122, 123, 124]
* The COVID-19 pandemic impacted the number of reviews in 2020, but the number of reviews show an increase in popularity of Sicily as a tourist destination. [cite: 126, 127, 128]

## Color Blindness Testing

The dashboards were tested for color blindness using the Pilestone simulator to ensure accessibility. [cite: 129, 130]
