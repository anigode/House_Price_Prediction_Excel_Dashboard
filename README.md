# House Price Prediction Dashboard
## Introduction
This project implements a House Price Prediction Dashboard using Microsoft Excel. The goal is to analyze house prices based on key features such as area, location, condition, garage availability, and year built. The dashboard offers an interactive experience for users to explore data trends and insights.

## Usage
- Load the dataset into Excel.
- Use Pivot Tables, Charts, and Slicers to interact with the data.
- Analyze trends and relationships based on the dashboard filters such as Area Bracket, Location, Condition, and Price Bracket.
- Customize the dashboard by adding more features or charts as needed.

## Data
The project uses a dataset containing house-related features. Key attributes include:
- Area: Total square footage of the house.
- Bedrooms & Bathrooms: Number of bedrooms and bathrooms.
- Floors: Number of floors in the house.
- Year Built: The year the house was constructed.
- Location: Urban, Suburban, Downtown, or Rural areas.
- Condition: Rating of the house condition (Excellent, Good, Fair, Poor).
- Garage: Availability of a garage (Yes or No).
- Price: Selling price of the house (categorized into Low, Medium, High, Premium brackets).

## Data Preprocessing
The dataset was preprocessed to include:
- Feature Engineering: Grouping Year Built, Area, and Price into brackets for better insights.
- Categorization: Transforming continuous variables into ranges.
- Cleaning: Ensuring consistency in data for analysis.

## Dashboard
The dashboard contains the following visualizations:
- Average Price by Area Bracket: A bar chart showing the relationship between area size and price brackets.
- Price Trends by Year Built: A line chart comparing price averages across construction eras.
- Price by Location: A bar chart highlighting the impact of location on house prices.
- Price by Condition: A stacked bar chart showing how condition impacts pricing.
- Price by Floors and Garage: A line chart visualizing price variations based on floor count and garage availability.

## Insights
### Area vs. Price
  - Larger houses (Extra Large, Large) dominate the Premium price category.
  - Smaller homes fall predominantly into Low or Medium price ranges.
### Location vs. Price
- Houses in Downtown and Urban areas command higher prices compared to Rural or Suburban areas.
### Condition vs. Price
- Houses rated as Excellent mostly appear in High and Premium brackets.
- Poor-condition houses rarely exceed Medium prices.
### Garage and Floors vs. Price
- Houses with a garage consistently have higher prices.
- Three-floor houses with a garage are priced the highest on average.
### Year Built vs. Price
- Houses built Post-2000 have significantly higher average prices compared to older constructions.

#### Libraries and Tools
This project leverages the following tools:
- Microsoft Excel: For data visualization and interactive dashboards.
- Pivot Tables and Charts: To summarize and visualize data.
- Slicers: For filtering data dynamically.
