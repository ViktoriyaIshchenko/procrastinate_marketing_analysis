# Real Estate Listings Analysis (Yandex.RealEstate)

## Project Description  
This project analyzes historical apartment listing data from Yandex.RealEstate. The goal is to determine the market value of real estate properties and identify the key factors influencing pricing. Based on the findings, we aim to define parameters for building an automated system that detects pricing anomalies and potential fraudulent activities.  

The dataset includes both user-input features and system-generated data, such as distances to parks, airports, and the city center.  

## Objectives  
1. Learn to estimate the market price of residential real estate.  
2. Identify the main factors that influence apartment pricing.  
3. Define parameters for an anomaly detection system to combat fraud.  

## Dataset Description  
The dataset includes various characteristics of apartments listed for sale:

- `airports_nearest` — distance to the nearest airport (in meters)  
- `balcony` — number of balconies  
- `ceiling_height` — ceiling height (in meters)  
- `cityCenters_nearest` — distance to the city center (in meters)  
- `days_exposition` — number of days the listing was active  
- `first_day_exposition` — publication date  
- `floor` — floor number  
- `floors_total` — total number of floors in the building  
- `is_apartment` — whether the listing is an apartment (boolean)  
- `kitchen_area` — kitchen area (m²)  
- `last_price` — listing price at removal  
- `living_area` — living area (m²)  
- `locality_name` — name of the locality  
- `open_plan` — open floor plan (boolean)  
- `parks_around3000` — number of parks within 3 km  
- `parks_nearest` — distance to the nearest park (in meters)  
- `ponds_around3000` — number of water bodies within 3 km  
- `ponds_nearest` — distance to the nearest water body (in meters)  
- `rooms` — number of rooms  
- `studio` — whether the apartment is a studio (boolean)  
- `total_area` — total area (m²)  
- `total_images` — number of photos in the listing  

## Project Workflow  
The research includes the following stages:  

1. **Data Overview**  
2. **Data Preprocessing**  
3. **Feature Engineering**  
4. **Exploratory Data Analysis**  
5. **Conclusions and Recommendations**  

## Tools & Technologies  
- **Python**  
- **pandas**  
- **matplotlib**, **seaborn**  

## Author  
This project was completed as part of a data analysis training program.  
