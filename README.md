🏅 Olympic Data Analysis Web App
📌 Live App

👉 Streamlit Deployment:
https://olympic-data-analysis-web-app-am3jfyvy4gxsad7yi4xbug.streamlit.app/

📖 Overview

This interactive Olympic Data Analysis Web App allows users to explore over 120 years of Olympic history using powerful visualizations and analytics.
Built with Python, Pandas, Plotly, Seaborn, and Streamlit, the app provides insights into:

🥇 Country performance over time

🧍‍♂️ Athlete demographics (age, height, weight)

🎯 Most successful athletes and nations

📅 Trends in participation throughout Olympic history

🏆 Medal tallies by year, country, and sport

The app uses the official Olympics dataset (athlete_events.csv) and country mapping (noc_regions.csv) to generate dynamic, high-quality visualizations.

🚀 Features
🔹 Home Dashboard

Summary of total athletes, sports, nations, and medals.

Timeline visualizations and participation trends.

🔹 Medal Tally Analyzer

View medals by:

Year

Country

Sport

Dynamic filtering and visual output.

🔹 Athlete Analysis

Age distribution plots

Height–Weight scatterplots

Gender-based comparisons

Medal-winning athlete patterns

🔹 Country-wise Deep Dive

Most successful athletes from a selected country

Sport-wise medal charts

Participation timeline

🔹 Global Trends

Line charts showing growth of countries, events, and athletes over years.

🗂️ Project Structure
├── app.py                 # Main Streamlit app
├── helper.py              # Data transformation utilities
├── preprocessor.py        # Data cleaning and merging
├── athlete_events.csv.gz  # Compressed dataset (<25 MB for Streamlit)
├── noc_regions.csv        # Country–region mapping
├── requirements.txt       # Dependencies for Streamlit Cloud
└── README.md              # Project documentation

🛠️ Installation (Local Setup)

Clone the repo:

git clone https://github.com/Goofyparag/olympic-data-analysis-web-app.git
cd olympic-data-analysis-web-app


Install dependencies:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run app.py

📊 Dataset Information
1. athlete_events.csv

Contains historical Olympic athlete data (1896–2016)

Includes:

Age, Height, Weight

Year, City, Sport, Event

Medal information

Nationality (NOC)

2. noc_regions.csv

Maps National Olympic Committee (NOC) codes to:

Full country name

Region

🧰 Tech Stack
Component	Technology
Web Framework	Streamlit
Data Processing	Pandas, NumPy
Visualization	Plotly, Seaborn, Matplotlib
Deployment	Streamlit Community Cloud
Language	Python 3.10+
📦 Requirements

Your requirements.txt includes:

streamlit
pandas
numpy
plotly
seaborn
matplotlib
scipy

🌟 Screenshots (Optional — add if needed)

You can add screenshots like:

![Home Dashboard](images/dashboard.png)
![Medal Analysis](images/medal_analysis.png)

🙌 Acknowledgements

Dataset sourced from:
📊 Kaggle — 120 Years of Olympic History
https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

📬 Contact

Author: Parag Tiwari
📧 Email: paragt2005@gmail.com
🔗 GitHub: https://github.com/Goofyparag

⭐ Support

If you like this project, consider giving the repository a ⭐ star on GitHub!
