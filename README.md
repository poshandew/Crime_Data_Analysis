# 🕵️‍♂️ Crime Data Analysis & Prediction

This project performs exploratory data analysis and predictive modeling on Indian crime data to uncover patterns, detect trends, and predict the likelihood of case closure.

## 📁 Dataset

Includes fields like:
- Date Reported, City, Victim Age, Gender
- Crime Code & Description
- Police Deployed, Case Closed status
- Time to solve the case (Case Solving Days)

## 🔍 Key Insights
- Cities with longest/shortest case resolution times
- Which crimes take longest to solve?
- Case-solving time distribution
- Correlation of victim age and gender with closure rate

## 🤖 Predictive Modeling
Using Random Forest Classifier to predict whether a case will be closed or not.

### 🔢 Features Importance:
- Case Solving Days
- Crime Code
- Victim Age
- City

## 📈 Visualizations
Included via Seaborn and Matplotlib:
- Histograms, bar plots, heatmaps
- Feature importance plots

## 📄 Final Report
Check the `outputs/` folder for a polished report in PDF/HTML format.

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
