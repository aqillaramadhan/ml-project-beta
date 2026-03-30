# ⚽ Sports Analytics: The "Moneyball" of Football

![Python](https://img.shields.io/badge/Python-3.14-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Data_Visualization-4EBA97.svg)

## 📌 Project Overview
Proyek **Exploratory Data Analysis (EDA)** ini membedah dataset raksasa EA Sports FC 24 (mengandung data 180.000+ pemain sepak bola profesional) untuk menemukan *hidden insight* di industri olahraga.

Proyek ini dirancang untuk menjawab mitos-mitos besar di dunia sepak bola menggunakan data yang akurat.

## 🕵️‍♂️ Key Insights & Findings
1. **The Golden Age:** Berdasarkan kurva performa, usia keemasan (puncak rating) seorang pemain sepak bola berada di rentang umur **28 hingga 33 tahun**.
2. **The Elites Factory:** **Spanyol** adalah negara pencetak pemain berstatus elit (Rating 85+) terbanyak di dunia, disusul oleh Jerman dan Prancis.
3. **The Exponential Value:** Hubungan antara *Skill* (Rating) dan Harga Pasar (*Value*) bukanlah garis lurus (linear), melainkan **Eksponensial**. Pemain dengan rating di atas 85 harganya meroket tajam puluhan kali lipat dibanding pemain ber-rating 75.

## 🛠️ Tech Stack
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 🚀 How to Run Locally
Karena ukuran dataset yang sangat besar, file CSV tidak disertakan di repository ini. 
1. Download dataset `male_players.csv` dari [Kaggle: EA Sports FC 24 Dataset](https://www.kaggle.com/datasets/stefanoleone992/ea-sports-fc-24-complete-player-dataset).
2. Letakkan file tersebut di folder utama (sejajar dengan file notebook).
3. Install dependencies menggunakan `pip install -r requirements.txt`.
4. Jalankan `01_Football_EDA.ipynb`.