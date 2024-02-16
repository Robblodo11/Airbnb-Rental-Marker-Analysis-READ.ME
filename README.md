# Airbnb-Rental-Market-Analysis-READ.ME
This Read.Me provides an overview of the Manhattan vacation rental market analysis project, outlining key steps and objectives for each part of the analysis. For detailed instructions and insights, refer to the corresponding sections in the project documentation.
https://tinyurl.com/Airbnb-Rental-Market-Project
## Table of Contents

### Introduction

#### Part 1: Explore and Filter the Data
* Explore the Data
* Prepare Tabs for Documentation
* Organize the Spreadsheet
* Filter Listings

#### Part 2: Which Type of Properties Should Be Targeted?
* Estimating Rental Activity
* Attractive Neighborhoods
* Popular Property Sizes
  
#### Part 3: Calculating Occupancy
* Preparing Data
* Average Occupancy for Each Listing
* Occupancy Rates by Day of the Week
  
#### Part 4: Estimate Revenue for an Investment Property
* Filtering Properties
* Adding Occupancy Rates to Listings
* Calculating Revenue

#### Part 5: What Attributes Are Important for a Vacation Rental?
* Impact of Superhosts
* Effect of Instant Booking
* Doorman Services and Review Scores
* Impact of Review Ratings on Prices

#### Part 6: Documentation and Spreadsheet Formatting
* Executive Summary
* Documentation of Data Cleaning Steps
* Formatting

#### Conclusion



### Introduction
You’ve been hired by a consulting company to analyze the vacation rental market in the Manhattan borough of New York City for a client interested in investing in properties. The client is interested in investing in several properties but would like some guidance on what types of properties they should be targeting. The project goal is to analyze data collected on current Airbnb listings to identify useful insights.

#### Part 1: Explore and Filter the Data
* Explore the Data
  * Downloaded the NYC Airbnb dataset and review the sheets
* Prepare Tabs for Documentation
  * Documented the data cleaning steps and versions of the final project file
* Organize the Spreadsheet
  * Freezed rows and columns, resized widths, and added filters
* Filter Listings
  * Filtered out irrelevant listings such as listings that have never been rented (inactive rentals), and rentals with a minimum night required of 8 days or higher
  
#### Part 2: Which Type of Properties Should Be Targeted?
* Estimating Rental Activity
  * Used number of reviews as an estimate for rental frequency
* Attractive Neighborhoods
  * Cleaned neighborhood labels and determined top 10 most poular neighborhoods for vacation rentals based on highest # of reviews
* Popular Property Sizes
  * Cleaned bedrooms data and analyzed property size preferences
  
#### Part 3: Calculating Occupancy
* Preparing Data
  * Converted availability column to numeric values and added day of the week column
* Average Occupancy for Each Listing
  * Calculated average occupancy rates for each listing by determining the average of the occupied column
* Occupancy Rates by Day of the Week
  * Analyzed occupancy rates based on weekdays vs. weekends
  
#### Part 4: Estimate Revenue for an Investment Property
* Filtering Properties
  * Filtered representative properties based on specific criteria
* Adding Occupancy Rates to Listings
  * Incorporated average occupancy rates into the listings by using a pivot table
* Calculating Revenue
  * Estimated annual revenue for selected properties by mulitplying 365 days for the year times the average price times the occupancy rate.
  
#### Part 5: What Attributes Are Important for a Vacation Rental?
* Investigated the impact of various attributes on property performance like can superhosts charge higher prices and do hosts who that offer instant booking have higher occupancy rates?

#### Part 6: Documentation and Spreadsheet Formatting
* Executive Summary
  * Provided an overview of recommendations.
* Documentation of Data Cleaning Steps
  * Documented assumptions and steps taken for data cleaning.
* Formatting
  * Enhanced spreadsheet readability with formatting techniques.
 
#### Conclusion
* Amongst all vacation rentals in the top 10 neighborhoods in Manhattan, 1 bedroom apartments have the largest sum of reviews, or amount of times the apartment has been rented, with a grand total of 16,691 reviews (estimated # of times listing was rented) Refer to Most Popular # of Bedrooms in top 10 Neighborhoods
* Recommend to investor to Invest in properties with 1 bedroom in Midtown. The estimated annual revenue from midtown properties with 1 bedroom is $99,912. In order to calculate estimated annual revenue, you need to mulitply 365 days for the year times the average price times the occupancy rate. Refer to Average Price & Occupancy Rate Pivot Table
* Buildings with Doormen do not show a difference in Check in ratings when compared to buidlings without doormen. When the 2 are compared, both show an average rating of 4.9 stars whether the building has a doorman or not. Refer to Building Staff vs Checkin Ratings Pivot Table
* Hosts can and do charge higher prices on average for listings with higher review ratings. Refer to Review Scores Rating vs Average Price Pivot Table




