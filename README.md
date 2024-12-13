# User Behavior and Order Analysis

This repository contains an analysis of user behavior, cooking preferences, and order trends based on datasets provided for an interview assignment. The analysis explores user demographics, dish popularity, time of day patterns, and ratings to generate actionable insights for business growth.

## Objective

The goal of this analysis is to:
- Examine the relationship between cooking sessions and user orders.
- Identify popular dishes based on order counts and revenue.
- Analyze user behavior trends, focusing on meal preferences, time of day, and ratings.
- Provide insights and recommendations for business strategy.

## Datasets

1. **UserDetails**: Contains information about users such as User ID, Name, Age, Location, Favorite Meal, and Total Orders.
2. **CookingSessions**: Includes session details with information on Session ID, User ID, Dish Name, Meal Type, Session Duration, and Session Rating.
3. **OrderDetails**: Covers user order details, including Order ID, User ID, Meal Type, Dish Name, Order Status, Amount (USD), Time of Day, Rating, and Session ID.

## Key Insights

### 1. **Popular Dishes by Revenue**:
   - **Spaghetti**: 9 orders
   - **Grilled Chicken**: 9 orders
   - **Caesar Salad**: 7 orders
   - **Pancakes**: 6 orders
   - **Veggie Burger**: 4 orders
   - **Oatmeal**: 3 orders

   **Insight**: Spaghetti and Grilled Chicken are the most popular dishes in terms of order frequency. Focus on optimizing these dishes for higher sales.

### 2. **Order Count by Time of Day**:
   - **Night**: 18 orders
   - **Day**: 11 orders
   - **Morning**: 9 orders

   **Insight**: Orders are most frequent at night. Consider promoting meals for breakfast and lunch to balance the order distribution.

### 3. **Average Spend by Time of Day**:
   - **Day**: $10.00
   - **Morning**: $7.83
   - **Night**: $13.31

   **Insight**: Users tend to spend more during the night. Special offers or discounts could encourage higher spending during other times of day.

### 4. **Average Rating by Dish**:
   - **Caesar Salad**: 4.00
   - **Grilled Chicken**: 4.54
   - **Oatmeal**: 4.00
   - **Pancakes**: 4.00
   - **Spaghetti**: 4.44
   - **Veggie Burger**: 4.21

   **Insight**: Grilled Chicken has the highest average rating, suggesting a strong customer preference. Consider focusing on improving other dishes like Caesar Salad and Oatmeal.

## Growth Suggestions

1. **Promote High-Rated Dishes**: Focus on high-rated dishes like Grilled Chicken to build customer loyalty and enhance brand image.
2. **Offer Promotions for Daytime Meals**: Create discounts or bundle offers for breakfast and lunch to increase sales during the daytime.
3. **Enhance Customer Engagement at Night**: Since the highest revenue is generated during night orders, offering exclusive late-night deals could increase order volume.
4. **Experiment with Menu Diversity**: Try introducing more variations of top-rated dishes (e.g., new versions of Grilled Chicken) and collect user feedback to further improve the menu.

## Repository Structure

- **`UserDetails.csv`**: User demographic data.
- **`CookingSessions.csv`**: Data on cooking sessions and their ratings.
- **`OrderDetails.csv`**: Data related to orders placed by users.
- **`Analysis.ipynb`**: Jupyter notebook for data analysis and visualizations.
- **`visualizations/`**: Folder containing generated plots and graphs.
- **`README.md`**: This document summarizing the analysis and insights.

## How to Run the Code

1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn

