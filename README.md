# Airbnb-listings-and-Reveiw-Analysis--Python-Project
An exploratory data analysis of Airbnb Paris listings using Python, Pandas, and Matplotlib. Analyzes pricing variations across neighborhoods and accommodation sizes, and quantifies the impact of 2015 French short-term rental regulations on new host registrations and market pricing trends.

**Project Overview
**An in-depth exploratory data analysis of Airbnb listings in Paris, examining pricing patterns across neighborhoods, accommodation sizes, and temporal trends. This project investigates the impact of 2015 French short-term rental regulations on host growth and pricing dynamics.
S - Situation
The sharing economy, particularly short-term rental platforms like Airbnb, has transformed urban tourism markets. Paris, one of the world's most visited cities, implemented regulations in 2015 to control short-term rentals. Understanding how these regulations affected host participation and pricing is crucial for policymakers, hosts, and travelers.
**Business Problem:
**How do Airbnb prices vary across Paris neighborhoods?
What is the relationship between accommodation capacity and pricing?
Did the 2015 regulations impact new host registrations and listing prices?

Task
My objectives were to:

Clean and prepare the Airbnb listings dataset for Paris-specific analysis
Perform quality assurance to identify data completeness and statistical distributions
Analyze pricing patterns across neighborhoods and accommodation sizes
Investigate temporal trends in host registrations and pricing from pre- to post-regulation periods
Visualize insights through effective charts and graphs
Derive actionable insights about regulatory impact on the Paris Airbnb market
Action
1. Data Preparation & Quality Assurance

Imported the Listings.csv dataset using pandas
Converted date columns to datetime format for temporal analysis
Filtered data to Paris listings only, retaining key columns: host_since, neighbourhood, city, accommodates, and price
Conducted comprehensive QA:

Checked for missing values across all columns
Calculated descriptive statistics (min, max, mean) for numeric fields
Ensured data integrity before analysis

2. Neighborhood Pricing Analysis

Created paris_listings_neighbourhood table grouping listings by neighborhood
Calculated mean prices per neighborhood and sorted from lowest to highest
Identified the most expensive neighborhood for deeper analysis
Generated horizontal bar chart visualizing average prices across all Paris neighborhoods

Accommodation Size Analysis

Built paris_listings_accommodations table focusing on the most expensive neighborhood
Grouped by accommodation capacity (accommodates column)
Calculated mean prices for each accommodation size
Created horizontal bar chart showing price variations by guest capacity

4. Temporal Trend Analysis

Constructed paris_listings_over_time table grouped by host registration year
Calculated two key metrics per year:

Average listing price
Count of new hosts (new listings)

Generated dual-axis line chart showing both metrics over time
Set y-axis limits to zero for accurate visual comparison
Applied proper titles and axis labels for clarity

Regulatory Impact Assessment

Analyzed trends before and after 2015 regulation implementation
Compared new host growth rates pre- and post-regulation
Examined pricing trajectory changes around the regulatory period
Synthesized findings into actionable insights

Results
Key Findings:
Neighborhood Pricing Insights:
Significant price variation across Paris neighborhoods, with central/tourist areas commanding premium rates
The most expensive neighborhood showed clear correlation between accommodation size and price
Budget-friendly neighborhoods identified for cost-conscious travelers

Accommodation Capacity Patterns:

Strong positive correlation between number of guests accommodated and price
Larger properties (4+ guests) in expensive neighborhoods showed disproportionately higher prices
Sweet spot identified for value: 2-3 person accommodations
Regulatory Impact (2015 Regulations):

New Host Growth: Noticeable slowdown or plateau in new host registrations following 2015 regulations, indicating regulatory barriers to entry
Price Dynamics: Average prices showed stabilization or modest increase post-2015, suggesting:

Reduced supply led to sustained/increased prices
Regulations may have filtered out lower-quality/lower-priced listings
Professional hosts with compliant listings maintained market presence

**Business Impact:
**
The 2015 regulations achieved their intended effect of controlling Airbnb growth in Paris
Existing hosts benefited from reduced competition and stable/higher prices
Travelers faced a more limited but potentially higher-quality listing pool
Regulatory compliance created barriers favoring established, professional hosts

**Technologies Used
**
Python 3.x
Pandas - Data manipulation and analysis
Matplotlib - Data visualisation
Jupyter Notebook - Interactive development environment
Visualizations Included

Horizontal bar chart: Average price by neighbourhood
Horizontal bar chart: Average price by accommodation size (most expensive neighborhood)
Line chart: New hosts count over time
Line chart: Average price over time
Dual-axis line chart: New hosts and average price trends combined

**Key Insights
**
📊 Market Segmentation: Paris Airbnb market shows clear price stratification by neighborhood and property size
📉 Regulatory Effect: 2015 regulations successfully curbed new host growth, stabilizing the market
💰 Pricing Stability: Post-regulation prices remained stable or increased, benefiting compliant hosts
🏠 Quality Over Quantity: Regulations shifted market toward fewer, potentially higher-quality listings

