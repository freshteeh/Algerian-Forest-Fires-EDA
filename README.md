# Algerian Forest Fires Data Analysis & EDA

# Algerian Forest Fires Data Analysis & EDA

This repository contains the data cleaning process and Exploratory Data Analysis (EDA) for the **Algerian Forest Fires Dataset**[cite: 12]. The dataset covers observations from two regions in Algeria (Bejaia and Sidi-Bel Abbes) collected between June and September 2012[cite: 12].

## 📊 Dataset Overview
The dataset contains instances with weather observations and Fire Weather Index (FWI) system components[cite: 12]:
* **Date:** Day, month (June to September), and year (2012)[cite: 12]
* **Weather Observations:** Temperature (max), Relative Humidity (RH), Wind Speed (Ws), and Rain[cite: 12]
* **FWI Components:** FFMC, DMC, DC, ISI, BUI, and FWI[cite: 12]
* **Classes:** Classified into `fire` and `not fire` categories[cite: 12]

## 🛠️ Project Steps
1. **Data Cleaning:** Handling missing values, creating and splitting data by region, stripping whitespaces from column names, and converting data types to appropriate numeric formats.
2. **Exploratory Data Analysis (EDA):** Generating statistical visualizations, class distribution pie charts, and analyzing the correlation matrix between weather variables and forest fire indicators.

## 🚀 Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
