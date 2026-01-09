# 🌸 Iris Flower Classification

## Project Summary
This project tackles the classic "Hello World" problem of Data Science: classifying Iris flowers based on their physical measurements. The objective was to build a model capable of distinguishing between Setosa, Versicolor, and Virginica species using pattern recognition rather than manual rules.

## Development Environment
* **IDE:** Google Colab (Jupyter Notebook environment)
* **Language:** Python 3.x

## Methodology
The workflow was straightforward but covered essential machine learning steps:
1.  **Data Preprocessing:** I started by loading the dataset and verifying the data quality. Columns that offered no predictive value, such as 'Id', were removed to keep the model focused.
2.  **Model Selection:** I chose the **Random Forest Classifier** for this task. It is robust and generally outperforms simpler models by averaging multiple decision trees, which reduces the risk of overfitting.
3.  **Training & Testing:** The data was split into an 80/20 ratio. This ensured that the model was evaluated on unseen data, providing a fair assessment of its real-world performance.

## Key Results
The model achieved **100% accuracy** on the test set. While this is rare in complex real-world scenarios, it is expected for the Iris dataset given how distinct the physical features of these flower species are.

---
*Submitted by Siddhi for the CodeAlpha Internship.*
