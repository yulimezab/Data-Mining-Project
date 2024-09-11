# Flight Price Prediction

![Diseño sin título](https://raw.githubusercontent.com/yulimezab/Data-Mining-Project/main/images/travel.png)

## Project Overview
This project is divided into multiple deliveries, each focusing on different aspects of data mining, from data selection and exploration to migration, modeling, and dashboard presentation.

---

## Delivery 1: Data Selection  
**Due Date: 16/08/2024**

### Dataset Chosen
The dataset selected for the **"Flight Price Prediction"** project comprises **300,261 datapoints** and **11 features**. This data was scraped from the **"Ease My Trip"** website, covering flight bookings between India's top 6 metro cities over a 50-day period in early 2022.

### Dataset Description

#### Features
- **Airline**: The carrier operating the flight. Helps analyze pricing strategies of different airlines.
- **Source City**: The city from which the flight departs. Allows examination of regional price variations.
- **Destination City**: The city where the flight lands. Helps understand price differences based on destination demand.
- **Departure Time**: The scheduled time when the flight departs. Useful for analyzing how different times of day affect prices.
- **Arrival Time**: The scheduled time when the flight arrives. Helps in understanding how arrival schedules influence pricing.
- **Ticket Class**: The class of the ticket (e.g., Economy, Business). Allows comparison of pricing between different ticket classes.
- **Days Left**: The number of days remaining until departure. Critical for analyzing the impact of booking timing on prices.

#### Data Quality and Coverage
- **Data Completeness**: The dataset is extensive, but may have missing values or incomplete records, especially for features like departure and arrival times.
- **Data Accuracy**: The accuracy is based on the scraping process and source reliability. Some discrepancies in ticket prices and times may exist.

---

## Justification

The chosen dataset is well-suited for analyzing and predicting flight prices due to its comprehensive nature and relevance to the project goals.

### Potential Insights
1. **Price Variation by Airline**: Analyze how different airlines set their prices, revealing competitive pricing strategies.
2. **Impact of Booking Time**: Investigate how the number of days left until departure affects ticket prices.
3. **Effect of Departure and Arrival Times**: Examine how different flight times impact prices.
4. **Class-Based Price Differences**: Compare pricing between economy and business class tickets.

### Expanded Methodology
1. **Data Preprocessing**: Clean the dataset by addressing missing values, encoding categorical variables, and scaling continuous variables if necessary.
2. **Exploratory Data Analysis (EDA)**: Utilize statistical summaries and visualizations to understand feature distributions and relationships.
3. **Statistical Analysis**: Perform correlation analysis and ANOVA tests to understand feature impacts on pricing.
4. **Predictive Modeling**: Develop linear regression models and explore advanced techniques like decision trees and ensemble methods.
5. **Model Evaluation**: Use cross-validation and performance metrics (MAE, RMSE) to assess and refine models.

---

## Relevance

The dataset aligns closely with the project goals and research questions. Here’s how each feature addresses the research questions:

- **Airline**: Helps in understanding price variations by comparing how different airlines price their tickets under similar conditions. This feature can reveal competitive pricing strategies and brand-specific pricing patterns.
- **Days Left**: Allows analysis of how booking timing influences ticket prices. By examining how prices change as the departure date approaches, we can identify trends in pricing strategies related to booking timing.
- **Departure and Arrival Times**: Facilitates examination of how different flight times impact prices. This helps understand if flights during peak hours or specific times of the day are priced differently.
- **Ticket Class**: Provides insights into class-based pricing differences. By comparing economy and business class prices, we can determine the pricing strategies for different levels of service and amenities.

### Examples of Similar Studies

- **Dynamic Pricing in Airlines**: A study by **Zhang et al. (2021)** used similar datasets to explore dynamic pricing models in the airline industry, revealing how factors like booking time and demand affect ticket prices. They applied machine learning techniques to predict price changes and optimize revenue management.
- **Airline Pricing Strategies**: **Chen and Yang (2019)** conducted research on airline pricing strategies using datasets with features like departure times and ticket classes. Their study focused on how airlines adjust prices based on demand, competition, and time of booking.
- **Impact of Departure Times on Pricing**: Research by **Hsu and Tsai (2020)** examined how departure and arrival times influence flight prices. Their analysis highlighted price patterns associated with different times of day and peak travel periods, using data similar to what is available in this dataset.




---



