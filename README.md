# Project Name: Iris Flower Classification

### Intern Information
* **Intern ID:** CITS1320
* **Full Name:** Patchigulla Jaya Kumar
* **Project Name:** Iris Flower Classification
* **No. of Weeks:** 2 weeks

---

## Project Scope & Overview
This project focuses on the classic machine learning problem of predicting the species of an iris flower based on its morphological measurements. Using the iconic Iris dataset from Kaggle, the project implements a complete data pipeline including data cleaning, exploratory data analysis with statistical visualizations, predictive modeling using a classification algorithm, and an interactive operational dashboard.

## Key Features & Steps Performed
* **Data Cleaning:** Loaded the raw `Iris.csv` dataset, dropped non-predictive indices (`Id`), verified data integrity, and checked for missing null data values.
* **Visualization & Analysis:** Generated a high-dimensional pairplot matrix and feature boxplots to explore how features like petal length and width distinguish the three distinct species (*Iris-setosa*, *Iris-versicolor*, *Iris-virginica*).
* **Prediction Models:** Split data into an 80/20 train-test ratio and trained a **K-Nearest Neighbors (KNN)** Classifier achieving optimal multi-class accuracy. Evaluated results via a confusion matrix heatmap.
* **Dashboard Creation:** Developed a fully functioning, interactive user application using Streamlit with custom measurement sliders to evaluate real-time flower classifications.

## Project Folder Directory Structure
Ensure your project files are arranged in your repository in the following manner:
```text
iris_classification_project/
│
├── Iris.csv                    <-- [DATASET FILES]
├── iris_classification.ipynb   <-- [NOTEBOOK/CODE] (Jupyter Notebook Analysis)
├── app.py                      <-- [NOTEBOOK/CODE] (Streamlit Dashboard Source)
├── README.md                   <-- [DOCUMENTATION] (This File)
│
└── screenshots/                <-- [GRAPHS & CHARTS / OUTPUT SCREENSHOTS]
    ├── iris_pairplot.png
    ├── iris_boxplot.png
    ├── iris_confusion_matrix.png
    └── dashboard_screenshot.png