# Real Estate Price Prediction

This project involves scraping real estate data, cleaning and processing it, and building a machine learning model to predict property prices based on various features.

## Features

- **Data Scraping**: The project uses web scraping techniques to collect real estate listings from an online platform, extracting details such as property prices, location, area, number of rooms, and additional information like utilities and nearby facilities.
  
- **Data Processing**: The scraped data is cleaned and preprocessed, including steps like:
  - Removing outliers.
  - Handling missing values.
  - Converting data types for analysis.

- **Text Manipulation**: Text data, such as property descriptions, is processed by:
  - Removing stopwords.
  - Normalizing text.
  - Extracting relevant keywords (e.g., utilities, conditions).

- **Exploratory Data Analysis (EDA)**: Visualizations are created to analyze relationships in the data, including:
  - Area vs. price.
  - Most common locations and price distributions.

- **Machine Learning**: A Random Forest Regressor is used to predict property prices, with hyperparameter tuning through GridSearchCV to improve model performance.

- **Evaluation**: The model's performance is assessed using metrics like Mean Squared Error (MSE) and R-squared score.