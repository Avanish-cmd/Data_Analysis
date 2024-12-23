# Data_Analysis
The objective of this assignment is to analyze datasets related to user behavior, cooking preferences, and order trends.

# User Behavior and Order Trends Analysis

This repository contains the code and data used for analyzing user behavior and order trends related to cooking and food delivery.

**Project Description:**

This project analyzes three datasets – UserDetails, CookingSessions, and OrderDetails – to understand the relationship between cooking habits and food ordering behavior. The analysis includes data cleaning and preprocessing, data merging, exploratory data analysis with visualizations, and the derivation of business recommendations based on the findings. The goal is to provide insights into user preferences, order patterns, and the impact of cooking on ordering behavior.

**Data Used:**

* User details (userdetails.csv)
* Cooking sessions (cookingsessions.csv)
* Order details (orderdetails.csv)

**Analysis Steps:**

1.  **Data Cleaning and Preprocessing:**
    *   Converted date and time columns to datetime format.
    *   Handled missing values and converted relevant columns to numeric types.
    *   Standardized the "Time of Day" column.
    *   Calculated cooking session durations accurately.
2.  **Data Merging:** Merged the three datasets based on `User ID` and `Session ID` to create a comprehensive dataset.
3.  **Exploratory Data Analysis (EDA):**
    *   Analyzed the frequency of cooked and ordered dishes.
    *   Examined the distribution of meal types for cooking and orders.
    *   Investigated the relationship between cooking sessions and total orders using correlation analysis and regression plots.
    *   Analyzed order status distribution and calculated the cancellation rate.
    *   Explored user demographics (age distribution and orders by location).
    *   Analyzed the distribution of cooking session durations.
    *   Calculated the average rating of orders associated with cooking sessions.

**Key Findings:**

*   Certain dishes like Spaghetti and Grilled Chicken are both frequently cooked and ordered, suggesting these are popular choices.
*   There is a slight positive correlation between the number of cooking sessions and total orders, indicating that users who cook more tend to order more as well.
*   A notable order cancellation rate suggests a potential issue with the ordering process or user experience.
*   Orders linked to cooking sessions tend to have higher average ratings, implying a positive impact of cooking on customer satisfaction.
*   Users across different locations show varying order frequencies, highlighting potential regional preferences.
*   The age distribution of users offers insights into the target demographic.

**Business Recommendations:**

*   Promote cooking sessions for popular dishes (e.g., Spaghetti, Grilled Chicken) to potentially increase user engagement.
  
*   Offer targeted promotions based on location (e.g., specific meal deals in certain areas).

*   Address the relatively high cancellation rate ({cancellation_rate:.2f}%) by investigating the reasons for cancellations and implementing appropriate measures.

*   Since there is a slight positive correlation between cooking sessions and total orders ({correlation:.2f}), encourage users to cook more to potentially increase their order frequency.

*   Orders associated with cooking sessions have an average rating of {average_rating_with_session:.2f}. Thus, promoting cooking sessions can result in higher customer satisfaction.

**Author:**

Avanish Yadav 

**Contact:**

kumaravanish885@gmail.com
avanishkumar1813072@akgec.ac.in

**License:**

(Specify the license under which you are sharing your code, e.g., MIT License)
