# Restaurant Data Analysis Project

## Overview

This project involves a comprehensive data analysis of a restaurant dataset to uncover key trends, patterns, and relationships within the restaurant industry. Conducted as part of an internship at **Cognifyz Technologies**, this analysis provides insights into various aspects, from restaurant performance and geographical distribution to service offerings and customer preferences.

## Project Objectives

The primary goals of this project were to:

1.  **Analyze Restaurant Ratings:** Understand the distribution of aggregate ratings and identify cities with exceptionally high average ratings.
2.  **Explore Cuisine Preferences:** Identify the most common cuisine types and combinations, and analyze their average ratings.
3.  **Geographical Distribution:** Visualize the spatial distribution of restaurants and identify areas with high concentrations.
4.  **Chain Analysis:** Identify restaurant chains within the dataset and analyze their ratings and popularity.
5.  **Review Text Analysis (Partial):** Analyze available rating text to identify common words associated with positive and negative sentiments.
6.  **Votes and Ratings Correlation:** Investigate the relationship between the number of votes a restaurant receives and its aggregate rating.
7.  **Price Range vs. Services:** Determine if there's a correlation between a restaurant's price range and the availability of online delivery and table booking services.

## Dataset

The dataset used for this analysis contains various attributes related to restaurants, including:
* Restaurant ID
* Restaurant Name
* Location details (Country Code, City, Address, Locality, Longitude, Latitude)
* Cuisines
* Cost and Currency information
* Service availability (Table Booking, Online Delivery)
* Price range
* Aggregate rating, Rating color, Rating text, and Votes

*(Note: The dataset did not contain a dedicated 'Review Text' column for in-depth sentiment analysis. The 'Rating text' column was used for a limited analysis of associated words.)*

## Analysis & Key Findings

Through various analytical and visualization techniques, the project yielded several key insights:

* **Rating Distribution:** The majority of restaurants fall into the 3-4 aggregate rating range, indicating a generally good performance, though a significant portion also had very low (0-1) ratings.
* **Top Cuisines:** "North Indian", "Chinese", and "Fast Food" emerged as the most common cuisines. Interestingly, "Cafe" combinations showed higher average ratings than some individual common cuisines like "North Indian".
* **Geographical Hotspots:** Restaurant concentrations were prominently observed in regions corresponding to parts of the United States (Eastern), India (Subcontinent), and Australia (Eastern coast).
* **Restaurant Chains:** "Barbeque Nation" was identified as a leading chain, excelling in both average ratings and total customer engagement (votes) among the top chains.
* **Votes vs. Ratings:** A weak positive correlation was observed between the number of votes and the aggregate rating, suggesting that more popular restaurants tend to have slightly better ratings, but the relationship is not absolute.
* **Service Availability by Price:** Online delivery was found to be most prevalent among mid-priced restaurants (Price Range 2), while table booking showed a strong positive correlation with higher price ranges (Price Ranges 3 and 4).

## Tools and Technologies Used

* **Python:** The primary programming language for analysis.
* **Pandas:** For data manipulation and analysis.
* **Matplotlib:** For creating static, interactive, and animated visualizations.
* **Seaborn:** For statistical data visualization.
* **Folium:** For interactive geographical mapping.
* **NLTK:** For basic text processing (tokenization, stop word removal) for 'Rating text' analysis.

## Acknowledgements

This project was completed as part of my internship experience at **Cognifyz Technologies**. I am grateful for the opportunity to apply and enhance my data analysis skills in a practical setting.
