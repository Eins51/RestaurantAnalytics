# Restaurant Data Analytics

## Project Overview
This repository contains code and datasets for analyzing restaurant data sourced from Google BigQuery. The aim is to provide insights into customer check-in behaviors, restaurant popularity, market analysis based on geographical and temporal data points, and so on.

## Features
- Data extraction from Google BigQuery.
- Data preprocessing including data cleaning and data transformation.
- Analytical visualizations of check-in data across different cities and price ranges.
- Implementation of data aggregation and analysis using Python Pandas and visualization using Tableau.

## Installation
To set up this project locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/Eins51/RestaurantAnalytics.git
   ```

2. Navigate to the project directory:

   ```
   cd RestaurantAnalytics
   ```

3. Install required Python packages:

   ```
   pip install -r requirements.txt
   ```

## Usage
1. Run the Jupyter Notebook for data preprocessing and analysis:

   ```
   jupyter notebook notebooks/restaurant_data_analysis.ipynb
   ```

2. Explore the Tableau dashboards for interactive visualizations:

   - Dashboard 1: Market Trends and Spending Insights
     - Analyze restaurant distribution, spending trends, and high-potential regions.
     - [Video Demo](https://github.com/Eins51/RestaurantAnalytics/blob/master/tableau/videos/market_trends_and_spending_insights.mp4)
     - ![Dashboard 1 Preview](https://github.com/Eins51/RestaurantAnalytics/blob/master/tableau/screenshots/overview1.png)
     - ![Dashboard 1 Video Demo](https://github.com/Eins51/RestaurantAnalytics/blob/master/tableau/videos/market_trends_and_spending_insights.gif)
   - Dashboard 2: Peak and Off-Peak Customer Behavior
     - Understand peak dining hours, months, and consumer trends.
     - [Video Demo](https://github.com/Eins51/RestaurantAnalytics/blob/master/tableau/videos/peak_and_off-Peak_customer_behavior.mp4)
     - ![Dashboard 2 Preview](https://github.com/Eins51/RestaurantAnalytics/blob/master/tableau/screenshots/overview3.png)
     - ![Dashboard 2 Video Demo](https://github.com/Eins51/RestaurantAnalytics/blob/master/tableau/videos/peak_and_off-Peak_customer_behavior.gif)

## Data Preprocessing

- **Data Acquisition**: Data was sourced from public Google Cloud Storage buckets and loaded into Google BigQuery.
- **Data Cleaning**: Removed duplicates, handled missing values, and conducted feature engineering (e.g., geographic classification, temporal data enrichment).
- **Data Transformation**: Time data was binned for granular analysis, and datasets were simplified for focused analysis.

## Dashboards

### Dashboard 1: Market Trends and Spending Insights

- Key Metrics:

  - Total Restaurants: 8.5 million
  - Operational Restaurants: 6.8 million
  - Total Check-ins: 12 billion
  - Total Reviews: 4.5 billion
  - Average Rating: 4/5

- Visualizations:

  - Geographic distribution of restaurant activity.
  - Spending trends by state and city.
  - Seasonal consumer behavior insights.

- Insights:

  - High-potential regions include Pennsylvania, Florida, and Louisiana.
  - Seasonal trends show spending peaks in March, May, and July.

### Dashboard 2: Peak and Off-Peak Customer Behavior

- Key Metrics:

  - Peak Months: March, May, July
  - Off-Peak Months: January, September, November
  - Peak Hours: 11 PM to 1 AM
  - Off-Peak Hours: 8 AM to 10 AM

- Visualizations:

  - Hourly and monthly check-in patterns.
  - Peak traffic periods by location.

- Insights:

  - Late-night dining trends in urban areas.
  - Inventory and staffing optimization based on peak/off-peak patterns.

## Recommendations

1. **Expand Locations**: Focus on cities like Philadelphia, Tampa, and New Orleans with high consumer interest.

2. **Optimize Operating Hours**: Introduce late-night services (10 PM - 3 AM) in urban hotspots.

3. Seasonal Inventory Strategies:

   - Increase inventory during peak months (March, May, July).
   - Reduce inventory during off-peak months (January, September, November) to minimize waste.

## Acknowledgments

Special thanks to:

- The Google Cloud Platform team for providing the data.
- Tableau for powerful visualization tools.
- Contributors and collaborators who supported this project.

