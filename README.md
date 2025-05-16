# Smart-pricing-strategies-for-ride-sharing-apps-

## Dataset Overview

This project uses a real-time simulated dataset sourced from **Kaggle**, containing Uber and Lyft ride fare estimates along with corresponding weather data across key Boston locations. Data was collected through API queries at 5-minute intervals for ride prices and hourly for weather conditions, spanning late November to early December 2018.

###  Context
Unlike fixed public transport pricing, ride-sharing fares fluctuate based on real-time demand and supply. Factors such as time of day, weather, and city events can influence prices significantly. This dataset replicates these real-world dynamics to help analyze what triggers high-demand periods and pricing surges.

---

##  Project Goal

**Forecast peak demand periods** and **anticipate surge pricing** using time series analysis, helping optimize fare strategies for ride-sharing platforms.

---

##  What I Did

-  **Data Acquisition**: Sourced the dataset from **[Kaggle](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma)**, originally compiled via API queries.
-  **Data Preprocessing**: Cleaned and formatted the dataset, handled missing values, parsed timestamps, and aligned weather and ride data.
-  **Exploratory Data Analysis**: Visualized ride prices over time and assessed the influence of external factors like time of day and weather on fare dynamics.
-  **Feature Engineering**: Extracted temporal features (hour, weekday, etc.) and integrated weather metrics to enrich the model input.
-  **Time Series Forecasting**: Applied forecasting models to predict future ride prices and identify potential high-demand periods.
-  **Model Evaluation**: Evaluated prediction accuracy using metrics like RMSE and visual comparison to actual price trends.

---

##  Dataset Features
- **Cab Details**: Service type (Uber/Lyft), estimated fare, base price, and surge multipliers.
- **Timestamps**: Time of each price query at fine granularity.
- **Weather Conditions**: Hourly temperature, cloud cover, rain, and other features at corresponding locations.
- **Simulated Pricing**: Reflects what the ride would have cost at that moment; actual trips were not taken.

---

##  Use Case
- Predict **surge pricing windows** using historical trends.
- Support **dynamic pricing algorithms** for ride-sharing platforms.
- Evaluate how **external factors** (weather, time, etc.) drive demand.

---

##  Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Time series libraries (e.g., `statsmodels`, `prophet`)
- Jupyter Notebook
- Data sourced from [Kaggle Uber/Lyft Boston Dataset](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma)

---

##  Future Enhancements
- Incorporate local event data (e.g., sports games, concerts).
- Test advanced machine learning models (e.g., XGBoost, LSTM).
- Expand to multi-city or real-time data pipelines.

