# List_of_countries_by_GDP_Web_Scraping_Analysis
Web scraping and analysis of global GDP (Nominal) data from Wikipedia — including cleaning, EDA, and visualization with Python

# 🌍 GDP Analysis Project

This is my **first project** during my internship at **Codveda Technologies** 🚀.  
The goal was to analyze **Nominal GDP data** for more than 220 countries.  

---

## 🔹 Step 1: Web Scraping
- Collected data directly from **Wikipedia** using **BeautifulSoup** and **Requests**.  
- Faced issues with messy values like `[n 1]` or symbols (—).  
- Solved them using **Regular Expressions (re)** to extract only numeric values.  

---

## 🔹 Step 2: Data Cleaning & Processing
With **Pandas**, I:  
- Handled missing values.  
- Converted all columns into the correct data types (float & int).  
- Created **log-transformed features** to reduce skewness and make data easier to compare.  

---

## 🔹 Step 3: EDA & Visualization
I used multiple libraries for different purposes:  
- **Matplotlib & Seaborn** → subplots, heatmaps, distributions.  
- **Plotly** → interactive charts (Pie, Bar, Scatter).  

---

## 📊 Key Insights
- **Top 10 economies** (USA, China, India, Japan, Germany, etc.) = about **two-thirds of world GDP**.  
- **USA & China** dominate the global economy compared to the rest of the Top 10.  
- The distribution is very skewed, but using a **log scale** makes comparisons clearer.  
- **IMF, World Bank, and UN estimates** are almost the same (correlation > 0.98).  

---

## ✅ What’s Next
In the next project, I’ll be working on **clean datasets** and applying **Machine Learning for predictive modeling** 🤖.
