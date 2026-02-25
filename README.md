# Tourism Experience Analytics: Classification, Prediction, and Recommendation System

This project focuses on analyzing tourism data to understand user travel behavior, predict attraction ratings, classify visit modes, and recommend attractions based on user preferences.

The goal of this project is to transform tourism data into meaningful insights that help improve user experience and decision-making for tourism platforms.

> “Transforming tourism data into intelligent travel insights.”

---

## Problem Statement

Tourism platforms and travel agencies need better insights into user behavior to improve recommendations and customer satisfaction.  
However, large tourism datasets contain complex patterns that are difficult to analyze manually.

This project uses Machine Learning techniques to:

- Predict how users rate attractions
- Classify the type of visit (Family, Business, Friends, etc.)
- Recommend attractions based on user behavior and attraction features

---

## Project Type

- Machine Learning Project
- Data Analytics Project
- Recommendation System Project

---

## Domain

Tourism Analytics and Data Science

---

## Dataset Description

The dataset used in this project includes information about:

- Users
- Tourist attractions
- Cities and regions
- Countries and continents
- Visit type (mode)
- Ratings given by users

Main datasets used:

- transaction.xlsx
- user.xlsx
- city.xlsx
- item.xlsx
- continent.xlsx
- country.xlsx
- region.xlsx
- mode.xlsx
- type.xlsx

---

## Project Objectives

1. Build a Regression Model to predict attraction ratings.
2. Develop a Classification Model to predict visit mode.
3. Create a Recommendation System for suggesting attractions.
4. Analyze tourism patterns using data visualization.
5. Deploy the project using Streamlit.

---

## Skills Applied in This Project

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning
- Model Evaluation
- Recommendation Systems
- Streamlit App Development

---

## Machine Learning Models Used

### Regression Model

**Algorithm:** Random Forest Regressor  
**Purpose:** Predict user attraction ratings.

**Evaluation Metrics:**

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

**Model Performance:**

- RMSE: 0.54
- R² Score: 0.69

The model explains approximately **69% of the variance** in attraction ratings.

---

### Classification Model

**Algorithm:** Random Forest Classifier  
**Purpose:** Predict visit mode.

**Evaluation Metrics:**

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

**Model Performance:**

- Accuracy (With UserId): **54.96%**
- Accuracy (Without UserId): **52.34%**

This comparison helped understand the influence of user-specific behavior on prediction.

---

### Recommendation System

**Technique:** Content-Based Filtering

This system recommends attractions based on:

- Attraction type
- Location
- User behavior
- Historical visit data

---

## Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis  
4. Feature Engineering  
5. Machine Learning Modeling  
6. Model Evaluation  
7. Recommendation System  
8. Streamlit Deployment  

---

## Streamlit Application

A Streamlit web application was developed to make the project interactive.

The app allows users to:

- Predict attraction ratings
- Identify visit type
- Get attraction recommendations
- Explore tourism insights visually

The application was deployed using **ngrok + Streamlit**, enabling real-time model predictions through a web interface.

---

## Business Impact

This system helps tourism platforms to:

- Improve customer experience
- Provide personalized attraction recommendations
- Understand travel behavior patterns
- Optimize marketing strategies
- Increase user engagement

---

## Project Structure

```
Tourism-Experience-Analytics
│
├── Tourism_Experience_Analytics.ipynb   # Main project notebook
├── app.py                               # Streamlit application
├── README.md                            # Project documentation
│
├── datasets
│   ├── transaction.xlsx
│   ├── user.xlsx
│   ├── city.xlsx
│   ├── item.xlsx
│   ├── continent.xlsx
│   ├── country.xlsx
│   ├── region.xlsx
│   ├── mode.xlsx
│   └── type.xlsx
│
├── models
│   ├── regression_model.pkl
│   └── classification_model.pkl
│
└── images
    ├── app_screenshot.png
    └── model_results.png
```

---

## Methodology

The project follows a structured data science workflow.

### 1. Data Preprocessing

- Handling missing values
- Data merging
- Encoding categorical variables
- Feature selection

### 2. Exploratory Data Analysis

- User behavior analysis
- Attraction popularity analysis
- Seasonal tourism trends
- Data visualization

### 3. Feature Engineering

- Creating machine learning ready dataset
- Encoding location hierarchy
- Transforming categorical variables

### 4. Model Building

- Random Forest Regression
- Random Forest Classification
- Recommendation System

### 5. Model Evaluation

- RMSE
- R² Score
- Accuracy
- Confusion Matrix
- Feature Importance Analysis

---

## Key Insights from the Project

- User travel behavior varies across months.
- City-level tourism has strong influence on visit purpose.
- Attraction type plays a major role in tourism experience.
- User patterns significantly affect visit mode prediction.
- Personalized recommendation improves user engagement.

---

## Future Improvements

- Hyperparameter tuning
- Use advanced models like XGBoost
- Improve recommendation accuracy
- Handle class imbalance using SMOTE
- Deploy a full production-level web application
- Integrate real-time tourism data

---

## Conclusion

This project demonstrates how machine learning and data analytics can be used to improve tourism platforms.  
By predicting ratings, classifying visit modes, and recommending attractions, the system helps enhance personalized travel experiences.

The integration of machine learning models with a Streamlit application makes the solution interactive and practical for real-world tourism analytics.

---

## Author
**Dharminder Singh Virk**  
