# New-York-Airbnb-Data-from-2003-to-2022

## Project Portfolio can be found here: https://oil-octagon-e70.notion.site/Project-Portfolio-194a641f375380478404ef1198f2428c

## Columns in the dataset

### Numerical metrics

- daily_price - the daily price in local currency
- service_fee - Any additional fee
- minimum_nights - the minimum number of nights a guest must stay
- number_of_reviews - the number of reviews the listing has
- reviews_per_month - the number of reviews the listing has over the lifetime of the listing
- last_review - the date of the last/newest view
- availability_365 - the availability of the listing 365 days in the future as determined by the calendar; a listing may not be available because it has been booked by a guest or blocked by the host
- review_rate_number - overall guest satisfaction
- construction_year - the year the listing was built
- id - Airbnb's unique identifier for the listing
- host_id - Airbnb's unique identifier for the host/user
- lat - latitude coordinate
- long - longitude coordinate
- calculated_host_listings_count - the number of listings the host has in the current scrape, in the city/region geography

### Categorical dimensions

- name - name of the listing.
- host_name - name of the host. Usually just the first name(s)
- neighbourhood_group - specific boroughs of New York City
- neighborhood - specific neighborhood in New York
- room_type - all listings are grouped into private room, shared room, entire home/apt, or hotel
- cancellation_policy - all listings have a flexible, moderate, or strict cancellation policy
- instant_bookable - true or false; determines whether the guest can automatically book the listing without the host requiring to accept their booking request
- host_identity_verified - true or false; determines whether the identity of the host is verified or unconfirmed

## Goal

The goal of this project was to analyze the overall trends of New York Airbnb listing prices and review ratings from 2003 to 2022 using Excel. This project will involve data cleaning, statistical analysis, and visualization to determine how property features influence both pricing and ratings. Identifying these relationships can help Airbnb hosts make data-driven decisions to maximize revenue and improve guest experience. By understanding which factors contribute to higher pricing and better ratings, hosts can strategically enhance their properties and optimize pricing. Ultimately, this analysis provides insights that can lead to increased bookings, higher profitability, and long-term success on the platform.

## Process

I sourced an Airbnb dataset that contained  details on property characteristics, prices, and review ratings. I imported it into Excel for cleaning and analysis. To prepare the data, I standardized column formats, properly categorized values, and removed duplicates Using Excel functions and filters, I ensured data accuracy and categorized property features for better analysis. I then analyzed trends in Airbnb listing prices and review ratings using PivotTables to identify trends. Finally, I visualized the insights using PivotCharts and Slicers. These visualizations highlight key property attributes that influence listing prices and review ratings.

## Key Findings

1. Neighborhoods significantly influenced Airbnb prices, while room type had a moderate impact. Cancellation policy had minimal effect, indicating that guests are willing to spend more for specific locations and accommodation types over booking flexibility.
2. Neighborhoods strongly influenced Airbnb review ratings, while room type had a moderate impact. Cancellation policy played a minor role, suggesting guests prioritize location and accommodation type over booking flexibility.

