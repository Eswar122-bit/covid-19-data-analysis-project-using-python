# covid-19-data-analysis-project-using-python
Python script to analyze COVID-19 data using OWID or synthetic samples. Cleans and enriches datasets with metrics like CFR and vaccination gap, saves to CSV, and generates visualizations: total cases &amp; deaths trends, vaccination progress, and heatmaps of cases per million, with summary stats.
📌 Overview

This project analyzes COVID-19 datasets using Our World in Data
 or a synthetic fallback sample.
It cleans, enriches, and visualizes the data to explore pandemic trends, vaccination progress, and overall impact.

✨ Features

📥 Loads OWID COVID-19 dataset (auto-fallback to synthetic data if offline).

🧹 Cleans & preprocesses data, adds derived metrics:

Cases per million

Case fatality rate (CFR)

Vaccination gap

📊 Visualizations:

Daily new cases with rolling averages

Total cases & deaths trends

Vaccination progress (1 dose vs fully vaccinated)

Heatmap of cases per million across countries

📈 Simple regression (vaccination vs cases) if scikit-learn is available.

💾 Saves cleaned dataset as cleaned_covid_data.csv.

🛠 Requirements

Python 3.8+

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn requests

▶️ Usage

Clone the repo and run the script:

python covid_analysis.py


Outputs:

Cleaned CSV → cleaned_covid_data.csv

Visualizations (interactive plots)

Console summary stats

📊 Example Visuals

Vaccination progress

COVID impact heatmap (cases per million)

Cumulative cases & deaths

📜 License

MIT License – feel free to use and modify.
