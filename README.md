# Cyclistic Bike-Share
## Project overview
Analyze differences in usage between annual members and casual riders to identify actions that increase membership conversion and improve fleet operations.

## Business question
How do members and casual riders differ by frequency, trip duration, time patterns, and bike type, and which interventions will raise conversions and retention?

## Data
Source: Cyclistic trip history (monthly CSVs).

Key fields: ride_id, rideable_type, started_at, ended_at, start_station_name, end_station_name, start_lat, start_lng, end_lat, end_lng, member_casual.

## Analysis steps
1. Load and merge monthly CSVs.

2. Clean data: parse timestamps, compute ride_length (minutes), remove invalid/duplicate trips and extreme outliers.

3. Feature engineering: day_of_week, month, hour, ride_type, user_segment.

4. EDA & visuals: average ride length by user, rides by day/hour, heatmap hour×day, bike-type shares.

5. Comparative analysis: means/medians, seasonal and weekday/weekend patterns, statistical checks where useful.

6. Recommendations: targeted campaigns, pricing experiments, operational changes (redistribution, bike mix).

## How to run
1. Clone repo.

2. Place CSVs in data/.

3. Open Cyclistic-bike-share.Rmd (or notebook) and run chunks.

4. Requirements: R with tidyverse, lubridate, ggplot2 (or Python: pandas, matplotlib/seaborn if preferred).

## Deliverables
- Cyclistic-bike-share.Rmd or notebook (cleaning, EDA, visuals, recommendations).

- data/ (raw and cleaned).

- outputs/ (figures, summary tables, final report).

## Quick results summary
Casual riders take longer trips, especially on weekends; members ride shorter, more regular trips on weekdays. Target weekend/leisure offers and summer campaigns to lift conversion and adjust fleet allocation accordingly.

# Contact
Author: Ayman Afardi — AfardiAyman@Gmail.com 
