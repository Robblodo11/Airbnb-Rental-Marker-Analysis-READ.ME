# Airbnb-Rental-Market-Analysis-READ.ME
This Read.Me provides an overview of the Manhattan vacation rental market analysis project, outlining key steps and objectives for each part of the analysis. For detailed instructions and insights, refer to the corresponding sections in the project documentation.

## Demo Video
* https://www.loom.com/share/5f1efa7127f54060bc5e3b3a637391ae?sid=3c56dbc2-4080-46b0-b578-a0883e7fefe5

## Link to Project
* https://tinyurl.com/Airbnb-Rental-Market-Project

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
![Screen Shot 2024-02-16 at 12 41 41 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/2da909ae-b808-4750-bec6-e193ae75be17)
* Popular Property Sizes
  * Cleaned bedrooms data and analyzed property size preferences
![Screen Shot 2024-02-16 at 12 44 20 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/1a30b175-31e5-4f8a-a5ae-3c7cc9a99c93)
#### Part 3: Calculating Occupancy
* Preparing Data
  * Converted availability column to numeric values and added day of the week column
* Average Occupancy for Each Listing
  * Calculated average occupancy rates for each listing by determining the average of the occupied column
* Occupancy Rates by Day of the Week
  * Analyzed occupancy rates based on weekdays vs. weekends
![Screen Shot 2024-02-16 at 12 46 22 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/94b7124e-b403-4f7d-ba46-3aeea73e7955)
#### Part 4: Estimate Revenue for an Investment Property
* Filtering Properties
  * Filtered representative properties based on specific criteria
* Adding Occupancy Rates to Listings
  * Incorporated average occupancy rates into the listings by using a pivot table
* Calculating Revenue
  * Estimated annual revenue for selected properties by mulitplying 365 days for the year times the average price times the occupancy rate.

#### Part 5: What Attributes Are Important for a Vacation Rental?
* Investigated the impact of various attributes on property performance like do buildings with doormen get better review scores for check-in? and do hosts who that offer instant booking have higher occupancy rates?
![Screen Shot 2024-02-16 at 12 48 19 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/390be496-cf1f-4476-a1e6-f54786e43668)

![Screen Shot 2024-02-16 at 12 49 18 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/2f5981b5-775d-4d3e-b0a0-4602a7f3f2a6)
#### Part 6: Documentation and Spreadsheet Formatting
* Executive Summary
  * Provided an overview of recommendations.
![Screen Shot 2024-02-16 at 12 50 13 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/835978d1-c92d-4715-bbef-5e6de71c85c1) 
* Documentation of Data Cleaning Steps
  * Documented assumptions and steps taken for data cleaning.
![Screen Shot 2024-02-16 at 12 51 42 PM](https://github.com/Robblodo11/Airbnb-Rental-Marker-Analysis-READ.ME/assets/153016872/d0464a9b-ed0f-4a0e-851f-b78b55458b67)
* Formatting
  * Enhanced spreadsheet readability with formatting techniques.
#### Conclusion
* Amongst all vacation rentals in the top 10 neighborhoods in Manhattan, 1 bedroom apartments have the largest sum of reviews, or amount of times the apartment has been rented, with a grand total of 16,691 reviews (estimated # of times listing was rented) Refer to Most Popular # of Bedrooms in top 10 Neighborhoods
* Recommend to investor to Invest in properties with 1 bedroom in Midtown. The estimated annual revenue from midtown properties with 1 bedroom is $99,912. In order to calculate estimated annual revenue, you need to mulitply 365 days for the year times the average price times the occupancy rate. Refer to Average Price & Occupancy Rate Pivot Table
* Buildings with Doormen do not show a difference in Check in ratings when compared to buidlings without doormen. When the 2 are compared, both show an average rating of 4.9 stars whether the building has a doorman or not. Refer to Building Staff vs Checkin Ratings Pivot Table
* Hosts can and do charge higher prices on average for listings with higher review ratings. Refer to Review Scores Rating vs Average Price Pivot Table




