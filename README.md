# 🚀 IBM Applied Data Science Capstone

## SpaceX Falcon 9 First Stage Landing Prediction

### Project Overview

This project was completed as part of the IBM Applied Data Science Capstone. The objective is to analyze historical SpaceX Falcon 9 launch data and build machine learning models to predict whether the first stage of a Falcon 9 rocket will successfully land.

Successful first-stage recovery significantly reduces launch costs, making this prediction valuable for estimating future launch expenses and understanding the factors influencing mission success.

---

## Project Objectives

* Collect launch data using the SpaceX REST API and web scraping.
* Clean and preprocess the collected data.
* Perform exploratory data analysis (EDA).
* Execute SQL-based data analysis.
* Create interactive visualizations using Folium and Plotly Dash.
* Build and evaluate multiple machine learning classification models.
* Identify the best-performing predictive model.

---

## Dataset

The project combines data collected from:

* SpaceX REST API
* Wikipedia launch records

After preprocessing, the dataset contains information such as:

* Launch Site
* Booster Version
* Orbit
* Payload Mass
* Flight Number
* Landing Outcome
* Launch Success Class

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly Dash
* Folium
* Scikit-learn
* BeautifulSoup
* SQL

---

## Project Workflow

1. Data Collection
2. Data Wrangling
3. Exploratory Data Analysis
4. SQL Analysis
5. Interactive Map using Folium
6. Interactive Dashboard using Plotly Dash
7. Machine Learning Classification
8. Model Evaluation
9. Final Presentation

---

## Machine Learning Models

The following classification models were evaluated:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

The best-performing model achieved approximately **83.3% classification accuracy**.

---

## Key Results

* KSC LC-39A achieved the highest launch success ratio.
* Payload mass has a noticeable influence on launch success.
* Logistic Regression, SVM, and KNN achieved similar classification accuracy.
* Logistic Regression was selected as the final prediction model.

---

## Repository Structure

```
Data Collection/
Data Wrangling/
EDA/
SQL/
Folium Maps/
Plotly Dash/
Machine Learning/
Presentation/
README.md
```

---

## How to Run

```bash
git clone https://github.com/EngHKA/IBM-Applied-Data-Science-Capstone.git
cd IBM-Applied-Data-Science-Capstone
```

Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn plotly folium scikit-learn beautifulsoup4
```

Run the notebooks sequentially from Data Collection through Machine Learning.

---

## Author

**Hessa Alabdulmunem**

Computer Engineer

IBM Applied Data Science Capstone Project
