# 🏅 Olympic Data Analysis Web App

### 📌 Live App  
👉 **Streamlit Deployment:**  
https://olympic-data-analysis-web-app-am3jfyvy4gxsad7yi4xbug.streamlit.app/

---

## 📖 Overview

This **interactive Olympic Data Analysis Web App** allows users to explore **120+ years** of Olympic history through dynamic visualizations and meaningful analytics.

Built using **Python, Pandas, Plotly, Seaborn, Matplotlib, and Streamlit**, the app provides deep insights into:

- 🥇 Country performance over time  
- 🧍‍♂️ Athlete demographics (age, height, weight)  
- 🎯 Most successful athletes & nations  
- 📅 Trends in participation  
- 🏆 Medal tallies by year, country, and sport  

The app uses:
- `athlete_events.csv` → Historical Olympic dataset  
- `noc_regions.csv` → Country mapping  

---

## 🚀 Features

### 🔹 **Home Dashboard**
- Total athletes, nations, sports, and medal count  
- Timeline and participation trends  

### 🔹 **Medal Tally Analyzer**
Filter medals by:
- Year  
- Country  
- Sport  
Includes dynamic plots and medal counts  

### 🔹 **Athlete Analysis**
- Age distribution  
- Height vs Weight scatterplots  
- Gender-wise comparisons  
- Trends of medal-winning athletes  

### 🔹 **Country-wise Analysis**
- Most successful athletes from selected country  
- Medal performance by sport  
- Participation timeline  

### 🔹 **Global Trends**
- Line charts for growth of events, countries, and athletes over time  

---

## 🗂️ Project Structure

```
├── app.py                   # Main Streamlit app
├── helper.py                # Data transformation utilities
├── preprocessor.py          # Data cleaning & merging
├── athlete_events.csv.gz    # Compressed dataset (<25MB for deployment)
├── noc_regions.csv          # Country-region mapping
├── requirements.txt         # Dependencies
└── README.md                # Documentation
```

---

## 🛠️ Installation (Local Setup)

### **1. Clone the repository**
```bash
git clone https://github.com/Goofyparag/olympic-data-analysis-web-app.git
cd olympic-data-analysis-web-app
```

### **2. Install dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Streamlit app**
```bash
streamlit run app.py
```

---

## 📊 Dataset Information

### **athlete_events.csv**
Contains athlete data from **1896 to 2016**, including:
- Age, Height, Weight  
- Year, City, Sport, Event  
- Medal (Gold/Silver/Bronze)  
- NOC (Nationality)  

### **noc_regions.csv**
Maps NOC codes to:
- Country Name  
- Region  

---

## 🧰 Tech Stack

| Component       | Technology                       |
|----------------|-----------------------------------|
| Web Framework  | Streamlit                         |
| Data Processing| Pandas, NumPy                     |
| Visualization  | Plotly, Seaborn, Matplotlib       |
| Deployment     | Streamlit Community Cloud         |
| Language       | Python 3.10+                      |

---

## 📦 Requirements

Your `requirements.txt` should include:

```
streamlit
pandas
numpy
plotly
seaborn
matplotlib
scipy
```

---

## 🌟 Screenshots (Optional)

You can add screenshots here:

```
![Home Dashboard](link_here)
![Medal Analysis](link_here)
```

---

## 🙌 Acknowledgements

Dataset sourced from:  
📊 **Kaggle – 120 Years of Olympic History**  
https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

---

## 📬 Contact

**Author:** Parag Tiwari  
📧 Email: **paragt2005@gmail.com**  
🔗 GitHub: https://github.com/Goofyparag  

---

## ⭐ Support  
If you like this project, consider giving the repo a **⭐ star**!
