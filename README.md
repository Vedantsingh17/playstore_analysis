# 📱 Profitable App Profile – App Store Data Analysis

This project analyzes over 5,000 apps from the Google Play Store to identify the most profitable app categories based on user engagement, installs, and pricing.

---

## 🧠 Objective

To discover which app categories show the most potential for monetization and growth by analyzing:

- User Ratings
- Number of Reviews
- Install Counts
- App Pricing

---

## 📊 Tools Used

- **Python** 🐍
- **Pandas** – for data processing and cleaning
- **Matplotlib & Seaborn** – for visualization
- **SQL** *(Optional if using SQLite/PostgreSQL)* – for data extraction (if DB is used)

---

## 📁 Files

| File | Description |
|------|-------------|
| `cleaned_app_data_final.csv` | Cleaned dataset after removing outliers and formatting issues |
| `app_analysis.ipynb` | Main notebook with code, visualizations, and insights |
| `README.md` | Project overview |

---

## 🔧 Data Cleaning Steps

- Removed missing/null values
- Cleaned non-numeric formats (e.g. "1,000+" → `1000`)
- Converted install counts and prices to numeric format
- Filtered out irrelevant or corrupted rows (like apps with missing installs)

---

## 📈 Key Insights

- Certain categories like **Game**, **Communication**, and **Productivity** show high user engagement.
- Free apps dominate in install counts, but paid apps contribute significantly to revenue in some niches.
- Visualizations helped identify the **top 10 categories** by installs and **top apps by estimated revenue**.

---

## 🖼️ Sample Visualizations

- Bar charts of top app categories by installs
- Revenue potential by app price × installs
- Ratings vs. Reviews heatmaps

---

## 🚀 How to Run

1. Clone the repo or download the files
2. Open `app_analysis.ipynb` in **Jupyter Notebook** or **Google Colab**
3. Run the cells step-by-step

---

## 📬 Contact

Created by: Vedant Singh  
Email: vedantsingh4002@gmail.com  
LinkedIn: https://www.linkedin.com/in/vedant-singh-85696a251/

---

## 📝 License

This project is open-source and free to use for learning purposes.
