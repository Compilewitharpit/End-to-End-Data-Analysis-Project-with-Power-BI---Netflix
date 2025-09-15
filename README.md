# 📊 Netflix Data Cleaning & EDA Project

This project focuses on **data cleaning and exploratory data analysis (EDA)** using the [Netflix Movies & TV Shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows/data).  
The main objective is to clean, transform, and explore the dataset using **Power Query (Power BI)** and perform some basic **text sentiment analysis**.

---

## 📂 Dataset
- Source: [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)  
- Description: Contains metadata of TV shows and movies available on Netflix, including fields like title, director, cast, country, release year, rating, and more.  

---

## 🛠️ Tools & Technologies
- **Power BI (Power Query)** → For data cleaning and transformation  
- **Excel / CSV** → Raw dataset format  
- **Python (optional, for text analysis)** → For simple sentiment analysis  

---

## 🧹 Data Cleaning Steps
Data cleaning was performed in **Power Query**, which is the data engine of Power BI:

1. **Column profiling** – Checked column quality, distribution, and profile.  
2. **Handling empty values** – Identified and managed null/missing entries.  
3. **Encoding missing values** – Encoded categorical nulls for consistency.  
4. **Imputing with mode** – Replaced missing categorical values with the most frequent value.  
5. **Date cleaning** – Transformed date columns to proper formats.  
6. **Adding calculated columns** – Derived new columns (e.g., content length, release gap).  
7. **Splitting columns** – Broke multi-value fields (e.g., directors, cast).  
8. **Extracting values** – Extracted the first element (e.g., first genre, first country).  
9. **Simple text sentiment analysis** – Applied sentiment scoring on descriptions.  
10. **Filtering unnecessary data** – Removed duplicates & irrelevant records.  

---

## 🔎 Exploratory Data Analysis (EDA)
- Content distribution by **type (Movies vs TV Shows)**  
- Trend of **content released by year**  
- **Top countries** contributing content  
- **Most frequent ratings** assigned to Netflix titles  
- **Popular genres/categories**  
- **Sentiment distribution** of content descriptions  

---

## 📊 Visualizations
All analysis and charts were built using **Power BI dashboards**.  

*(Add screenshots of your Power BI dashboards here — e.g. `![Dashboard](screenshots.png)`) *

---

## 🚀 How to Use
1. Download the dataset from Kaggle: [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows/data).  
2. Open the Power BI project file (`.pbix`) or follow the Power Query steps.  
3. Explore the cleaned dataset and interactive dashboard.  

---

## 📌 Key Learnings
- Hands-on with **Power Query** for real-world data cleaning.  
- Techniques for handling missing data and creating calculated fields.  
- Basic **text sentiment analysis** on metadata.  
- Building **interactive dashboards** for storytelling with data.  

---

## 🙌 Acknowledgments
- Dataset by [Shivam Bansal on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).  
- Power Query & Power BI community resources.  

