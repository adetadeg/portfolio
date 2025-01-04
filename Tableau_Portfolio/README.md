# Cyclistic Bike-Share Analysis Case Study

## Business Task
The goal of this case study is to analyze how **annual members** and **casual riders** use Cyclistic bikes differently, based on historical trip data. By understanding these differences, the marketing team at Cyclistic aims to design strategies to convert casual riders into annual members, which will contribute to the company’s growth and long-term success. The insights from this analysis will be used to create targeted marketing campaigns to drive the conversion of casual riders into annual members.

## Data Overview
The data used in this case study comes from **Cyclistic’s** historical bike trip records. This dataset includes trip data for both casual riders and annual members, capturing various ride details such as ride length, start and end times, and the type of membership (annual or casual).

The data was prepared by performing the following:
- Cleaning and filtering ride data.
- Creating new calculated columns for `ride_length` and `day_of_week`.
- Aggregating the data based on rider type and other key variables.

## Analysis Process

### 1. **Ask**: Define the business task and key questions
- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- How can Cyclistic use digital media to influence casual riders to become members?

### 2. **Prepare**: Data cleaning and preparation
- Downloaded and stored the Cyclistic trip data for the past 12 months.
- Cleaned the data by removing duplicates and handling missing values.
- Created calculated columns to measure ride duration (`ride_length`) and the day of the week for each ride.

### 3. **Process**: Data transformation
- Applied necessary transformations to ensure the data was in the correct format.
- Merged trip data from different quarters to provide a full-year view.

### 4. **Analyze**: Data exploration and analysis
- Conducted descriptive analysis to compare ride length and frequency between casual riders and annual members.
- Used pivot tables and summary statistics to identify trends such as average ride duration by rider type and day of the week.

### 5. **Share**: Data visualization and insights
- Visualized key trends using bar charts, line graphs, and heatmaps.
- Provided clear and actionable insights into the differences in usage patterns between casual and annual riders.

### 6. **Act**: Recommendations and conclusions
- Based on the analysis, I have developed three top recommendations for the marketing team:
  1. **Target off-peak hours**: Promote annual memberships to riders during less busy times, where casual riders tend to use the bikes more.
  2. **Promote convenience and savings**: Highlight the cost-saving benefits of an annual membership in comparison to casual rides.
  3. **Leverage digital platforms**: Use social media ads and email marketing to target casual riders, offering them special promotions to encourage membership sign-ups.

## Files in This Repository
Here is the directory structure of the repository:

```bash
Cyclistic-Bike-Share-Analysis/
├── business_task.md            # Contains the business task statement
├── data/                       # Raw data files and datasets
│   ├── trip_data_1.csv
│   ├── trip_data_2.csv
│   └── ...
├── prepare/                    # Scripts and notebooks for data cleaning and preparation
│   ├── data_cleaning.py
│   └── data_preparation.ipynb
├── process/                    # Processed and cleaned data ready for analysis
│   └── cleaned_trip_data.csv
├── analyze/                    # Analysis notebooks or scripts
│   ├── data_analysis.py
│   └── exploratory_analysis.ipynb
├── share/                      # Visualizations and insights
│   ├── bike_usage_trends.png
│   └── ride_length_by_day.png
├── act/                        # Final recommendations and conclusions
│   └── marketing_recommendations.md
└── README.md                   # This file
