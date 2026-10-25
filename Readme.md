# 🏅 Olympic Insights Using Data Analytics

## Project Overview

This project analyzes historical Olympic data using Python, Pandas, Matplotlib, and basic machine learning techniques. It explores medal trends, athlete participation, country performance, and sports dominance, then uses Linear Regression to forecast future medal counts.

## Objectives

- Analyze historical medal trends of top countries.
- Explore athlete participation by gender, age group, and sport.
- Identify countries with major increases and decreases in medal counts.
- Analyze country dominance across specific sports.
- Forecast medal counts for selected countries using historical data.

## Technologies Used

- **Python** — Data analysis and modeling
- **Pandas** — Data cleaning and manipulation
- **Matplotlib** — Data visualization
- **NumPy** — Numerical operations
- **Scikit-learn** — Linear Regression and model evaluation
- **Jupyter Notebook** — Interactive analysis

## Project Structure

```text
Olympic_Data_Analytics/
│
├── Olympics_Country.csv
├── Olympics_Games.csv
├── Olympic_Results.csv
├── Olympic_Games_Medal_Tally.csv
├── Olympic_Athlete_Event_Results.csv
├── Olympic_Athlete_Bio.csv
│
├── 01_eda_medal_trends.ipynb
├── 02_olympic_medal_forecasting.ipynb
└── README.md
```

## Analysis Performed

### Part 1: Exploratory Data Analysis (EDA)

**1. Medal Trends Over Time**
- Selected the top five countries by historical medal totals.
- Visualized medal trends across Summer Olympic editions.

**2. Athlete Participation**
- Analyzed gender participation.
- Examined athlete age groups.
- Identified the top ten sports by unique athlete count.

**3. Country Performance Spikes and Dips**
- Calculated changes in medal counts between editions.
- Identified major medal increases and decreases.

**4. Country Dominance in Specific Sports**
- Compared country medal-winning records across sports.
- Visualized historical performance trends in Athletics.

### Part 2: Forecasting

- Prepared year-wise medal data for five countries.
- Trained a separate Linear Regression model for each country.
- Tested predictions against historical Olympic editions.
- Calculated Mean Absolute Error (MAE).
- Visualized historical trends and forecast medal counts.

The forecasting notebook includes China in place of the discontinued Soviet Union.

## How to Run the Project

1. Install Python and Visual Studio Code.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

3. Open the project folder in VS Code.
4. Open `01_eda_medal_trends.ipynb` to explore the EDA.
5. Open `02_olympic_medal_forecasting.ipynb` to explore forecasting.
6. Run the notebook cells in order.

Keep the CSV files in the same project folder as the notebooks, unless the notebook code specifies another path.

## Forecasting Limitations

- The dataset used for forecasting ends in 2020.
- Linear Regression assumes a simple linear relationship between year and medal count.
- Olympic results depend on many factors that a simple model cannot capture.
- Forecasts are estimates, not guaranteed outcomes.
- Country identities and historical participation can change over time.

## Key Learning Outcomes

- Data loading and manipulation with Pandas.
- Exploratory Data Analysis and visualization.
- Grouping, filtering, aggregation, and pivot tables.
- Time-series data preparation.
- Basic machine learning with Linear Regression.
- Prediction evaluation using MAE.
- Communicating findings and limitations.

## Conclusion

This project demonstrates how historical Olympic data can be used to discover participation patterns, compare country performance, visualize medal trends, and generate baseline medal forecasts using Python.

**Note:** Forecasts should be interpreted as educational estimates rather than official Olympic predictions.