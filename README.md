# Sea Level Predictor
### Python | Pandas | Matplotlib | Scipy (Linear Regression)

## 📌 Project Overview
This project analyzes a dataset of global average sea level change since 1880. Using Python's data science libraries, I developed a model to predict sea level rise through the year 2050. This demonstrates my ability to use historical data for trend forecasting and predictive analytics.

## 🛠️ Technical Workflow
* **Data Exploration:** Utilized **Pandas** to import and clean over 130 years of global sea level data.
* **Statistical Modeling:** Used `scipy.stats.linregress` to calculate the line of best fit for the entire dataset (1880-present).
* **Comparative Analysis:** Created a second regression line focusing only on data from the year 2000 onwards to show the acceleration in sea-level rise.
* **Visualization:** Generated a scatter plot with dual regression lines using **Matplotlib** to clearly communicate future projections.

## 📊 Key Results
* Successfully predicted sea level heights for the year 2050 based on current trends.
* Visualized the increasing rate of change in recent decades, proving the model's ability to handle non-linear growth patterns.

## 📂 Repository Structure
* `sea_level_predictor.py`: The core logic for data processing and modeling.
* `epa-sea-level.csv`: The primary dataset provided by the EPA.
