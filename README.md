# Seeds of Change: A Century of Climate and Crop Dynamics in India (1901–2021) 🌾

This project explores the evolving agricultural landscape of India, shaped by over a century of climatic shifts. Through extensive data analysis, visualization, and time-series forecasting, it investigates how changing patterns of rainfall and temperature have influenced crop dynamics, farming inputs, and overall agricultural resilience.

**Course:** Introduction to Data Science (2025)

## Team Members

* **Jaidev Sanjay Khalane** (22110103)
* **Vannsh Jani** (22110279)
* **John Twipraham Debbarma** (22110108)
* **Pranav Joshi** (22110197)

---

## Project Overview

India's agriculture is deeply intertwined with its climate, with over half the population dependent on farming. This project brings together over a century of data to answer key questions:

* How have temperature and rainfall patterns evolved across India from 1901 to 2021?
* Do high temperatures directly correlate with low rainfall?
* How do climate patterns and agricultural inputs (fertilizers, pesticides) correlate with crop yields?
* What are the future production trajectories for major crops?

## Features and Analysis Modules

1. **Automated Data Retrieval:** The script automatically downloads and extracts the required datasets from a remote GitHub repository.
2. **Climate Trend Analysis:** * Visualizes seasonal and annual temperature shifts over a century.
* Maps geospatial rainfall distribution using interactive GeoPandas plots.


3. **K-Means Clustering:** Groups data to uncover complex, non-linear relationships (e.g., identifying "warm and wet" vs. "cool and dry" years, and mapping yield against fertilizer/pesticide usage).
4. **Agricultural Exploratory Data Analysis (EDA):** Identifies top-producing states, highest-yielding crops, and distribution across farming seasons (Kharif vs. Rabi).
5. **Input Intensity Mapping:** Analyzes total vs. per-hectare usage of fertilizers and pesticides across different Indian states.
6. **Time-Series Forecasting (ARIMA):** Utilizes statistical modeling to predict the production volume of 11 key crops (including Rice, Wheat, Sugarcane, and Onion) for the next 5 years, complete with interactive dropdowns.

---

## Datasets Used

* **Sub-Divisional Monthly Rainfall (1901–2017):** Sourced from data.gov.in.
* **Seasonal and Annual Mean Temperature Series (1901–2021):** Sourced from data.gov.in.
* **Crop Yield in Indian States Dataset:** Sourced from Kaggle.
* **India Map GeoJSON:** Sourced from Kaggle for geospatial plotting.

---

## Prerequisites and Installation

To run this project, you need Python installed along with several data science libraries.

Run the following command to install the necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn geopandas ipywidgets requests

```

## How to Run


1. Open your Jupyter environment.
2. Execute the cells sequentially.

---

## Key Insights

* **Warming Trends:** Winter and pre-monsoon months are warming the fastest, reshaping traditional agricultural calendars.
* **Rainfall Variability:** While average temperatures are rising predictably, rainfall remains highly erratic and volatile.
* **Input vs. Yield:** High per-hectare usage of fertilizers and pesticides does not guarantee high yields. Clustering shows high yields are achieved across a wide spectrum of input intensities, suggesting soil health, water, and crop type play more decisive roles.
* **Crop Dominance:** Coastal and southern states show massive production weights driven heavily by specific crops (like Coconuts), while northern plains dominate in total cultivated area and sheer volume of staple grains (Wheat and Rice).

Colab Link: https://colab.research.google.com/drive/1Y1YCGvHRMOJct-LtZVrb7JyAvnG6qYQ6?usp=sharing
