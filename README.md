# Bike-Share-Operational-Optimization-Using-SQL

## Business Problem Statement
Citi Bike loses riders and revenue when high-demand stations run out of bikes during morning rush hour. How can we use trip data to optimize overnight bike redistribution and ensure stations are stocked for peak demand?

## Data Overview
3 million trips across 2,150 stations from 3 partitions of July 2024 [New York City Citi Bike data](https://s3.amazonaws.com/tripdata/index.html)

## Key Insights (July 2024 data)
**1. Morning Rush Imbalances (6-9 AM):** Stations like **W 43 St & 10 Ave** and **W 44 St & 11 Ave** lose 900-1000 bikes between 6-10 AM. 

**2. Evening Surplus:** Stations like **Christopher St & Greenwich St** and **West St & Chambers St** gain 1500 bikes between 5-8 PM. 

**3. User Behaviour:** 76.6% of trips are from annual members, confirming predictable weekday patterns.
 
**4.** The top morning deficit station and top evening surplus station are ~2.4 miles apart. Bikes moves from Midtown West to Downtown/West Village.

## Actionable Operational Recommendations
1. Redistribute bikes from evening surplus stations to morning shortage stations between 6-7 AM on weekdays. This will improve member commuter experience during peak demand.
2. Targeting high-impact locations (10 chronic shortages, 10 chronic surpluses) first will maximize operational efficiency.
3. Run dedicated overnight truck routes from Midtown West to Downtown/West Village. 
4. Move bikes in batches of ~300, which reduces loading/unloading time. 







