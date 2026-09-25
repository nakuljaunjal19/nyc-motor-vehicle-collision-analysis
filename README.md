
# New York Motor Vehicle Collision Analysis

This project analyzes motor vehicle collision data from New York City using Tableau. I looked at when collisions happen, where they occur most often, the main contributing factors, and areas with higher pedestrian and cyclist risk.

The detailed analysis focuses on Brooklyn.

## Tableau Dashboard

[View the interactive Tableau dashboard](https://public.tableau.com/app/profile/nakul.jaunjal/viz/NYCMotorVehicleAnalysis/Analysis)

## Dataset

- Dataset: NYC Motor Vehicle Collision Data
- Records: 993,930
- Date Range: July 2012 - March 2017
- Analysis Area: Brooklyn, New York

## Tools Used

- Tableau
- Google BigQuery
- Excel

## What I Analyzed

- Collisions by weekday
- Collisions by time of day
- Major contributing factors
- Collisions by ZIP code
- Collision locations and intersections
- Hourly collision trends by location
- Pedestrian and cyclist injuries and deaths
- Yearly collision trends

## Data Preparation

The dataset contained 48 different contributing factors. I grouped them into six broader categories so the results were easier to analyze:

- Driver Distraction / Inattention
- Bad Driving
- Health Issues
- Outside Distraction
- Driving Under the Influence
- Car Defects

Contributing-factor fields for vehicles 2-5 were not included in the main analysis because many of the values were unspecified or null.

Unspecified and null values were also excluded from the primary contributing-factor analysis.

## Contributing Factors and Time of Day

This dashboard compares collision patterns across weekdays, contributing factors, and different hours of the day.

Main findings:

- Saturday and Sunday had lower collision volumes than most weekdays.
- Driver Distraction / Inattention was the largest contributing-factor group.
- Collision activity was highest during the late afternoon, especially from around 3 PM to 6 PM.

![Contributing Factors and Time](images/overview.png)

## Collisions by Location

This dashboard looks at collisions by ZIP code, street, and intersection.

ZIP code 11201 was one of the areas with a high number of collisions.

![Collisions by Location](images/location-analysis.png)

## Location Hourly Trend

This dashboard compares collision activity by location and hour of day.

It helps show how collision patterns can change depending on the area and time. For example, ZIP code 11213 showed comparatively higher collision activity during some late-night hours.

![Location Hourly Trend](images/hourly-trend.png)

## Pedestrian and Cyclist Analysis

This dashboard focuses on pedestrian and cyclist injuries and deaths.

ZIP code 11206 stood out in this analysis. The dashboard can also be used to look more closely at streets and intersections within higher-risk areas.

![Pedestrian and Cyclist Analysis](images/injury-analysis.png)

## Recommendations

Based on the analysis:

- Focus distracted-driving awareness efforts on high-risk periods.
- Increase traffic monitoring during peak collision hours.
- Pay closer attention to high-collision ZIP codes and intersections.
- Use hourly collision patterns to help plan traffic enforcement at different times of day.
- Increase DUI checks in areas with higher late-night DUI-related collisions.
- Improve pedestrian crossings, cycling infrastructure, traffic signals, and signage in higher-risk areas.

## Tableau Workbook

The Tableau packaged workbook is included in this repository:

`NYC_Motor_Vehicle_Collision_Analysis.twbx`
