
# 🚗 Cars Dataset Visualization Project  

## 📖 Overview  
Analyzed the Cars dataset (1971–1983) using Python. After cleaning, multiple visualizations were created to study relationships between horsepower, mpg, weight, cylinders, time‑to‑60, year, and brand.  

---

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
- Handled missing values in **weightlbs** and **cubicinches**  
- Standardized brand names (US, Europe, Japan)  
- Converted year column to numeric format  
- Removed duplicates and ensured consistent data types  

---

## 📊 Visualizations  

### 🔴 Scatter Plots  
<img width="554" height="455" alt="image" src="https://github.com/user-attachments/assets/d8c1cb68-3455-4ec0-8154-4d7cf65e86c8" />

Shows relationships between horsepower and mpg, time-to-60, weight, and cylinders. Reveals negative and positive correlations across metrics.  

<Figure size 640x480 with 1 Axes><img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/abc3855a-66fe-4ba3-90c6-be15274e8bbc" />

Brand-colored scatter plot showing how fuel efficiency and horsepower vary across US, Europe, and Japan.  

<Figure size 1500x1000 with 4 Axes><img width="1246" height="855" alt="image" src="https://github.com/user-attachments/assets/379eea5d-94cf-4125-9b55-b47ccac26916" />

Four scatter plots comparing mpg, hp, time-to-60, and weight across brands. Highlights performance trade-offs.  

---

### 📈 Line Plots  
<Figure size 2000x1000 with 4 Axes><img width="1617" height="833" alt="image" src="https://github.com/user-attachments/assets/5aff7c1c-02f0-4781-96fb-efc54ca8a282" />

Line plots showing trends between horsepower, mpg, time-to-60, and weight. Each line uses a distinct color to show feature relationships.  

---

### 📊 Bar Plots  
<Figure size 1500x1000 with 4 Axes><img width="1246" height="855" alt="image" src="https://github.com/user-attachments/assets/0012f931-dbff-4587-aa03-78d6b2459775" />

Bar charts comparing cylinders with hp, mpg, weight, and time-to-60 across brands. Includes error bars and color coding.  

---

### 📦 Box Plots  
<Figure size 2000x1000 with 4 Axes><img width="1614" height="836" alt="image" src="https://github.com/user-attachments/assets/1995a268-0d9e-4495-a5ca-cb29473ef4ca" />
 
Box plots showing distribution and outliers for horsepower, mpg, weight, and time-to-60. Useful for spotting variability and extremes.  

---

### 🔍 Pair Plots  
<Figure size 1857.63x1750 with 56 Axes><img width="1845" height="1721" alt="image" src="https://github.com/user-attachments/assets/be9eb654-a98c-4e15-be80-5904861078b1" />

Scatter matrix showing relationships between all features. Diagonal plots show distributions. Color-coded by brand.  

---

### 🔥 Heatmap  
<Figure size 640x480 with 2 Axes><img width="603" height="486" alt="image" src="https://github.com/user-attachments/assets/ad1ce7ec-dc21-407b-9fe3-24c644dd343d" />
  
Correlation matrix showing how features relate. Strong negative and positive correlations are color-coded for clarity.  

---

### 📊 Histograms  
<Figure size 2000x1000 with 8 Axes><img width="1597" height="813" alt="image" src="https://github.com/user-attachments/assets/324dab96-d4e5-485a-83aa-8675aa4ed4e1" />

Histograms display the distribution of mpg, hp, weight, time‑to‑60, cubic inches, year, cylinders, and brand. These plots help in understanding spread, central tendency, and frequency of values across the dataset.  

---





## 🛠️ Technologies Used  
- **Python** – core programming language  
- **Pandas, NumPy** – data cleaning & manipulation  
- **Matplotlib, Seaborn** – visualizations (scatter, bar, box, histograms, heatmaps, etc.)  
- **Jupyter Notebook** – interactive environment for analysis  

---

## 🎯 Key Insights  
- US cars tend to have higher horsepower and lower mpg  
- Japanese and European cars show better fuel efficiency and lighter weight  
- Strong correlations exist between horsepower, weight, and acceleration  
- Fuel efficiency improved over time, especially in non-US brands  

---

## 🚀 How to Run  
1. Clone the repository  
2. Install required libraries:  
   ```bash  
   pip install pandas numpy matplotlib seaborn  
   ```  
3. Run the Jupyter Notebook or Python script  
4. Visualizations will be generated for each question  

---

✅ This README now includes **all your screenshots with explanations**.  

Would you like me to also **systematically rename your screenshot files** (e.g., `scatter_hp_mpg.png`, `histogram_mpg.png`) so they look cleaner and more professional in your repo?
