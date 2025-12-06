# 🚗 Cars Dataset Visualization Project  

## 📖 Overview  
Analyzed the Cars dataset (1971–1983) using Python. After cleaning, multiple visualizations were created to study relationships between horsepower, mpg, weight, cylinders, time‑to‑60, year, and brand.  

## 📂 Dataset  
- **Rows**: ~400  
- **Columns**: mpg, cylinders, cubic inches, hp, weight lbs, time‑to‑60, year, brand  
- **Brands**: US, Europe, Japan  

**Sample Records**  
| mpg  | cylinders | cubicinches | hp  | weightlbs | time-to-60 | year | brand  |  
|------|-----------|-------------|-----|-----------|------------|------|--------|  
| 14   | 8         | 350         | 165 | 4209      | 12         | 1972 | US     |  
| 31.9 | 4         | 89          | 71  | 1925      | 14         | 1980 | Europe |  
| 37.7 | 4         | 89          | 62  | 2050      | 17         | 1982 | Japan  |  

---

## 🧹 Data Cleaning  
- Handled missing values in **weightlbs** and **cubicinches**.  
- Standardized brand names (US, Europe, Japan).  
- Converted year column to numeric format.  
- Removed duplicates and ensured consistent data types.  

---

## 📊 Visualizations  
- **Scatter plots**: hp vs mpg, hp vs time‑to‑60, hp vs weight, hp vs cylinders, brand‑wise comparisons.  
- **Bar plots**: cylinders vs hp/mpg/weight, year vs hp/mpg/time‑to‑60, brand & year performance.  
- **Box plots**: hp, mpg, time‑to‑60, weight by cylinders and brand.  
- **Pair plots**: patterns across brand, cylinders, year.  
- **Heatmap**: correlation between numerical features.  
- **Histograms**: distribution of hp, mpg, time‑to‑60, weight, cubic inches, year, brand‑wise.  
- **Line plots**: hp, mpg, time‑to‑60, weight in one plane with distinct colors; feature comparisons.  
- **Pie charts**: distribution of brands and cylinders.  
- **Categorical plots**: hp, mpg, time‑to‑60, weight, cubic inches across brands and cylinders.  
- **Customized bar plots**: distinct colors, resized plots (20×15), red font color, font size 28.  

---



## 🛠️ Technologies Used  
- **Python** – core programming language  
- **Pandas, NumPy** – data cleaning & manipulation  
- **Matplotlib, Seaborn** – visualizations (scatter, bar, box, histograms, heatmaps, etc.)  
- **Jupyter Notebook** – interactive environment for analysis  

---

## 🎯 Key Insights  
- Performance differences across brands and cylinders are clear.  
- Strong correlations between horsepower, weight, and acceleration.  
- Fuel efficiency improved over years, especially in Japanese and European cars.  

---

