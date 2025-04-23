# Predicting Real Estate Prices in Bengaluru Using Machine Learning

## Project Overview
This project analyzes key factors affecting real estate prices in Bengaluru and develops a machine learning model to predict property values. The dataset includes features like location, size, total square footage, number of bathrooms, and balcony count.

## Problem Statement
The dynamic Bengaluru real estate market makes price estimation challenging for buyers, sellers, and investors. This model helps estimate fair market values by considering multiple property characteristics.

## Dataset
The dataset contains 13,320 property listings with features:
- area_type:

Describes the type of area (e.g., Super built-up Area, Plot Area, Built-up Area, Carpet Area).

Indicates the classification of the property's construction or land type.

- availability:

Specifies the availability status of the property (e.g., Ready To Move, a specific date like "19-Dec").

Indicates whether the property is immediately available or will be available by a certain date.

- location:

The neighborhood or locality where the property is situated (e.g., Electronic City Phase II, Whitefield).

Helps identify the geographical area of the property.

size:

Describes the size of the property in terms of bedrooms or BHK (e.g., 2 BHK, 4 Bedroom).

Indicates the number of bedrooms or the type of property.

society:

The name of the housing society or builder (e.g., Coomee, Theanmp).

Provides information about the developer or residential complex.

total_sqft:

The total area of the property in square feet (e.g., 1056, 2600).

May include ranges (e.g., "2100 - 2850") for some entries.

bath:

The number of bathrooms in the property (e.g., 2, 5).

Indicates the bathroom count for the property.

balcony:

The number of balconies in the property (e.g., 1, 3).

Some entries may have missing values (empty or NaN).

price:

The price of the property in lakhs (e.g., 39.07, 120).

Represents the cost of the property in Indian Rupees (1 lakh = 100,000 INR).
## Key Steps
1. Data exploration and cleaning
2. Feature engineering (created price_per_sqft, processed total_sqft)
3. Outlier detection and handling
4. Location binning (grouping rare locations)
5. [Add model development steps when completed]

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Bengaluru-Real-Estate-Price-Prediction.git
