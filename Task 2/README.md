# 🚗 Car Price Prediction

## Project Summary
In this task, I developed a machine learning model to estimate the selling price of used cars. This is a practical regression problem where the goal is to predict a continuous numerical value based on various attributes like the car's age, present market price, fuel type, and distance driven.

## Development Environment
* **IDE:** Google Colab (Jupyter Notebook environment)
* **Language:** Python 3.x

## Methodology
Predicting prices requires handling different types of data, so the process involved:
1.  **Feature Engineering:** The raw dataset contained text data (like "Petrol" or "Manual"). I used One-Hot Encoding (via Pandas) to convert these into numerical values that the algorithm could understand.
2.  **Model Implementation:** I implemented a **Linear Regression** model. Since price prediction often follows linear trends (e.g., as age increases, price decreases), this algorithm provided a solid baseline for estimation.
3.  **Visualization:** I plotted the predicted prices against the actual prices to visually confirm how well the model captured the market trends.

## Key Results
The model successfully identified the core factors driving car prices. The R-squared score confirmed a strong correlation between our predictions and the actual market values, making this a viable tool for price estimation.

---
*Submitted by Siddhi for the CodeAlpha Internship.*
