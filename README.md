# Predicting Real Estate Prices in Bengaluru Using Machine Learning

## Project Overview
This project analyzes key factors affecting real estate prices in Bengaluru and develops a machine learning model to predict property values. The dataset includes features like location, size, total square footage, number of bathrooms, and balcony count.

## Problem Statement
The dynamic Bengaluru real estate market makes price estimation challenging for buyers, sellers, and investors. This model helps estimate fair market values by considering multiple property characteristics.

## Dataset
The dataset contains 13,320 property listings with features:
- area_type: Describes the type of area (e.g., Super built-up Area, Plot Area, Built-up Area, Carpet Area). Indicates the classification of the property's construction or land type.

- availability: Specifies the availability status of the property. Indicates whether the property is immediately available or will be available by a certain date.

- location: The neighborhood or locality where the property is situated (e.g., Electronic City Phase II, Whitefield). Helps identify the geographical area of the property.

- size (converted to bedrooms): Describes the property size of bedrooms. Indicates the number of bedrooms or the type of property.

- society: The name of the housing society or builder. Provides information about the developer or residential complex.

- total_sqft: The total area of the property in square feet.

- bath: The number of bathrooms in the property.
  
- balcony: The number of balconies in the property.

- price (target variable): The price of the property in lakhs. This is the target column.

Represents the cost of the property in Indian Rupees (1 lakh = 100,000 INR).
## Key Steps
1. Data exploration and cleaning
2. Feature engineering (created price_per_sqft, processed total_sqft)
3. Outlier detection and handling
4. Location binning (grouping rare locations)
5. Model development (Linear Regression model)
6. Model evaluation using metrics like R² Score and cross-validation

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/gloriechris/Predicting-Real-Estate-Prices-in-Bengaluru-Using-Machine-Learning.git 
## Results & Insights

- Final model: Linear Regression
- R² Score on test set: 0.83
- Cross-validation score (mean): 0.80
- The model performs well and generalizes across the dataset.

**Insight**: Location and total_sqft are strong indicators of price. Outliers significantly affect the price-per-sqft feature and were handled to improve accuracy.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Folder Structure

---

### 5. **🚀 How to Run**
Give quick steps for other people:

```md
## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/gloriechris/Predicting-Real-Estate-Prices-in-Bengaluru-Using-Machine-Learning.git 
jupyter notebook House_Price_Prediction_Project.ipynb

pip install pandas numpy matplotlib seaborn scikit-learn


---

### 6. **💡 Future Improvements**
Show growth mindset 😉

```md
## Future Improvements

- Implement more complex models (e.g., XGBoost, Random Forest)
- Perform hyperparameter tuning
- Deploy model using Flask or Streamlit for web access



