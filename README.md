# Zomato Data Analysis

This project involves analyzing Zomato restaurant data to gain insights into various aspects such as customer preferences, ratings, and ordering patterns.
The dataset used for analysis contains information about different restaurants, including their names, online ordering availability, table booking options,
ratings, votes, approximate cost for two people, and the type of restaurant.

## Dataset Overview

The dataset consists of 148 entries and 7 columns:
- `name`: Name of the restaurant
- `online_order`: Availability of online ordering (Yes/No)
- `book_table`: Availability of table booking (Yes/No)
- `rate`: Rating of the restaurant
- `votes`: Number of votes received by the restaurant
- `approx_cost(for two people)`: Approximate cost for two people
- `listed_in(type)`: Type of restaurant

## Data Cleaning and Preprocessing

- The `rate` column's data type was converted to float, and the denominator was removed to standardize the ratings.
- No missing values were found in the dataset.
- The majority of restaurants fell into the dining category.
- Dining restaurants were preferred by a larger number of individuals based on the number of votes received.
- The restaurant "Empire Restaurant" received the maximum votes.
- A majority of the restaurants did not accept online orders.
- Ratings ranged mostly from 3.5 to 4.
- Most couples preferred restaurants with an approximate cost of around 300 rupees.
- Online orders received higher ratings compared to offline orders.

## Visualization

- Count plots were used to visualize the distribution of restaurants based on the type of cuisine and online ordering availability.
- A box plot was used to compare ratings between online and offline orders.
- A heatmap was created to visualize the relationship between the type of restaurant and online ordering availability.

## Conclusion

Based on the analysis, it was observed that dining restaurants were preferred over cafes, and online orders received higher ratings compared to offline orders.
These insights can help restaurants optimize their services and cater better to customer preferences.

