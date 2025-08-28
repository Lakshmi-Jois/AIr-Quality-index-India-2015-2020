Air Quality Index (AQI) Analysis in India (2015–2020)

🎯 Objective

To perform a comprehensive, data-driven analysis of air quality across Indian cities using Python. The project aims to identify:

- Pollution trends over time (2015–2020)
- Dominant pollutants and their sources
- Seasonal and festival-based variations
- City-wise air quality distribution

 📊 Dataset

- Source: https://www.kaggle.com/code/aditivirmani/air-quality-data-in-india-eda-av   
- Records: 29,531 rows × 16 columns
- Key columns: City, Date, PM2.5, PM10, AQI, CO, NO2, Benzene, etc.
- Cities covered: Delhi, Mumbai, Ahmedabad, Kolkata, Patna, and more.

🧹 Data Preprocessing

- Dropped columns with excessive missing values (e.g., NH3)
- Imputed PM2.5 and PM10 using city-wise mean values
- Removed remaining nulls for clean analysis
- Parsed and formatted dates for time series analysis

 📈 Exploratory Data Analysis (EDA)

- City-wise AQI comparison
- Pollutant distributions using histograms and boxplots
- Correlation matrix (e.g., PM2.5 vs AQI, Benzene vs Toluene)
- Diwali impact analysis on AQI (Delhi case study)
- Seasonal and year-wise trends in pollutant levels


 🧪 Test Cases

| Test Case        | Description                                   |
|-|-|
|                    |
| City-Based Split     | Test on smaller cities            |
| Seasonal Split       | Analyze winter vs monsoon pollution levels         |
| Festival Spike       | Compare Diwali vs normal day AQI in Delhi          |


 🔍 Key Insights

- PM10 (35.5%) and PM2.5 (20.2%) are the largest contributors to AQI
- Winter months show the highest pollution levels
- Delhi, Patna, and Ahmedabad face consistently poor air quality
- VOCs like Benzene and Xylene are high in industrial cities
- Diwali causes a significant temporary pollution spike


 🛠 Tools and Technologies

- Python (Pandas, Numpy)
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook
