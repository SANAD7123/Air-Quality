# Air-Quality
🌍 Air Quality Data Analysis Report
🧾 1. Introduction
This project analyzes the Air Quality UCI Dataset 📊, featuring hourly air pollution measurements 🌫️ and meteorological data 🌡️ across multiple variables.
________________________________________
🔍 2. Data Exploration
Initial exploration includes:
•	Dataset preview 👀
•	Summary statistics 📉
•	Data types and missing values ⚠️
•	Column uniqueness 🧬
________________________________________
🧼 3. Handling Missing Data
•	Missing data detected ✅
•	Dropped or imputed using mean values ➕  
•	Cleaned dataset ready for analysis 🧹
________________________________________
🎯 4. Project Objectives
🔎 Objective 1: Detect Most Missing Values
Checked missing value counts per column 📋
📏 Objective 2: Filter High CO Levels
Filtered rows where CO(GT) > 5 🚨
🧪 Objective 3: Impute Missing Data
Used .fillna() with mean values to clean dataset 📐
📈 Objective 4: Pollution Trends by Hour
Plotted average pollutant levels by hour 🕒
➡️ Found patterns in daily pollution cycles 🌤️🌙
📊 Objective 5: Time Series Visualization
Multivariate time series shows pollution peaks and trends over days 📅🕒
________________________________________
📡 5. Correlation & Covariance
•	📌 Heatmap reveals strong relations between pollutants
•	🔗 Covariance matrix calculated to explore linear relationships
________________________________________
⚠️ 6. Outlier Detection
•	Outliers found using IQR method 🧮
•	Visualized with bar plots and box plots 📦
•	Some variables showed significant anomalies 💥
________________________________________
🧠 7. Key Findings
•	CO & NOx show hourly variation 🚗
•	Strong correlation: CO & C6H6 🔄
•	Outliers present in several pollution indicators ❗
•	Hourly & daily trends suggest peak pollution periods 📆
________________________________________
✅ 8. Conclusion
This analysis delivers insights into urban air quality 🏙️
using Python tools 🐍 like pandas 🐼, seaborn 🎨, and matplotlib 📊
to empower environmental understanding and decisions 🌱
