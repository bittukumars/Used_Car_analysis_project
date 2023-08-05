# Used_Car_analysis_project

## About the Dataset

The dataset contains information on 2000+ used cars, including make, model, manufacturer, price, year of production, fuel type, states sold in, and kilometers driven. It provides valuable insights into the used car market, allowing users to understand popular models, manufacturer companies, and average prices in different states. The data on year of production and kilometers driven also offers additional information on vehicle age and condition, while the fuel type can help identify consumer preferences in various regions.

## Data Preparation

The data preparation process involved several steps using the Power Query Editor in Power BI:

1. Elimination of nulls, blank rows, and duplicate entries.
2. Generation of a unique identifier for each row called "Row ID," starting from 1000 and incrementing by 1 for each subsequent row.
3. Adjustment of data types for proper data representation.
4. Derivation of two new columns, "Brand" and "Car model," from the existing "car_name" column.
5. Removal of the original "car_name" column to maintain a streamlined dataset.

By performing these actions, the data was refined and optimized for further analysis and visualization.

## Data Analysis

The data analysis focused on extracting valuable insights from the used car market dataset. It covered the following aspects:

1. Analyzing the correlation between the age of a used car and its corresponding price.
2. Identifying the top 10 brands based on their average prices.
3. Determining the percentage of used cars in different cities for vehicles priced above 10 Lakh.
4. Examining the distribution of cars across low, middle, and high-end price categories based on both price and fuel type.

## Power BI Dashboard

The Power BI dashboard created provides a comprehensive overview of the used car market. It empowers users to explore the data, uncover meaningful insights, and make data-driven decisions based on the presented visualizations. The dashboard includes the following visualizations:

1. Line Plot: Visualizes the relationship between the age of a used car and its corresponding price. This helps understand how the price varies as cars age, identifying potential correlations or trends.

2. Bar Chart: Showcases the top 10 brands based on their average prices. Users can compare pricing across different brands and identify those commanding higher or lower prices in the market.

3. Pie Chart: Illustrates the percentage of used cars in different cities, focusing on cars with prices exceeding 10 Lakh. This helps identify cities with a higher concentration of expensive used cars, providing insights into regional market dynamics.

4. Multi-Row Card Visualization: Provides a summarized view of the number of cars in low, middle, and high-end price categories based on fuel type. This allows users to understand the distribution of cars across price ranges and fuel types.

## Conclusion

The Power BI dashboard offers a comprehensive analysis of the used car market, presenting key insights through interactive visualizations. Users can explore the relationships between price, age, brand, city, and fuel type, enabling them to make informed decisions based on the data. The provided analysis helps businesses and researchers gain valuable insights into the used car market and consumer preferences, facilitating data-driven decision-making.
