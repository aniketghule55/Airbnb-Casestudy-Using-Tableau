

# Airbnb Data Analysis

## Overview
This repository contains the analysis of a dataset consisting of 48,895 Airbnb listings. The goal of this analysis was to understand key market dynamics, pricing strategies, and host activity in various neighborhoods.

## Dataset
- **File:** `Cleaned Airbnb.csv`
- **Entries:** 48,895
- **Columns:** 14

### Columns:
- `host_id`: Unique identifier for each host.
- `host_name`: Name of the host.
- `neighbourhood_group`: Broader neighborhood group (e.g., Brooklyn, Manhattan).
- `neighbourhood`: Specific neighborhood within the group.
- `latitude` and `longitude`: Geographical coordinates for the listing.
- `room_type`: Type of room being offered (e.g., Entire home/apt, Private room).
- `price`: Price per night.
- `minimum_nights`: Minimum number of nights required for a stay.
- `number_of_reviews`: Total number of reviews the listing has received.
- `reviews_per_month`: Average number of reviews per month.
- `calculated_host_listings_count`: Number of listings the host has.
- `availability_365`: Number of days the listing is available in a year.

## Key Insights

1. **Room Type Distribution**
   - Majority of listings are either entire homes/apartments (52%) or private rooms (46%).
   - Shared rooms are relatively rare, constituting only 2% of the listings.

2. **Popular Neighborhoods**
   - Manhattan and Brooklyn are the most popular areas, accounting for 85% of all listings.
   - Queens, Bronx, and Staten Island have a smaller share of the market.

3. **Pricing Analysis**
   - Average nightly price is $152.72, with a significant range from $0 to $10,000.
   - The majority of listings (75%) are priced below $175 per night.

4. **Minimum Stay Requirements**
   - The average minimum stay is 7 nights, with most listings allowing a stay of 3 nights or fewer.
   - Some listings have extended minimum stay requirements, with a maximum of 1,250 nights.

5. **Host Activity**
   - While most hosts manage only 1-2 listings, a few are highly active with up to 327 properties.
   - This indicates a mix of individual hosts and professional property managers.

6. **Correlation Analysis**
   - A slight positive correlation between price and availability suggests that higher-priced listings tend to be more available.
   - Strong correlation between the number of reviews and reviews per month indicates that popular listings consistently engage customers.

## How to Use This Data
- **Market Analysis:** Use the insights to understand the dynamics of Airbnb listings in different neighborhoods.
- **Pricing Strategy:** Leverage the pricing analysis to optimize listing prices and understand market outliers.
- **Host Strategy:** Identify opportunities for new listings based on host activity and neighborhood popularity.
- **Customer Engagement:** Use the review data to enhance customer interaction strategies.

## Conclusion
This analysis provides a detailed understanding of Airbnb's market presence in various neighborhoods, pricing trends, and host behaviors. The insights can be leveraged for strategic decision-making in pricing, listing management, and customer engagement.

--
