# UK Food Consumption Analysis and PCA Visualization  

This project analyzes food consumption data across four regions in the UK (England, Northern Ireland, Scotland, and Wales) and uses Principal Component Analysis (PCA) to visualize which region differs the most in terms of food preferences.

---

## 📊 Project Overview  

The goal of this project is to:  
1. Analyze the consumption patterns of 17 food categories across the four UK regions.  
2. Apply **Principal Component Analysis (PCA)** to reduce the dimensions from 17 food items (features) to a single principal component for each region.  
3. Visualize the results to identify the most distinct region in terms of food consumption.

---

## 📂 Dataset  

The dataset includes:  
- **Regions:** England, Northern Ireland, Scotland, and Wales.  
- **Food Categories:** 17 food items with their respective consumption levels.

### Example of the dataset:

| Food Item          | England | N Ireland | Scotland | Wales |  
|---------------------|---------|-----------|----------|-------|  
| Milk (liters)       | 42.3    | 55.1      | 50.2     | 47.8  |  
| Bread (kg)          | 23.1    | 31.4      | 27.9     | 25.3  |  
| ...                 | ...     | ...       | ...      | ...   |  

---

## ⚙️ Methodology  

1. **Data Preprocessing:**  
   - Organized and normalized the dataset to ensure consistent units.  
   - Transposed the data to analyze food categories as features.  

2. **Principal Component Analysis (PCA):**  
   - Applied PCA to reduce the data dimensions from 4×17 to 4×1.  
   - Computed the principal components to identify the variation in food consumption patterns.

3. **Visualization:**  
   - Plotted the first principal component (PC1) to observe regional differences.  
   - Found that **Northern Ireland** has the most distinct food consumption pattern compared to other regions.

---

## 📈 Results  

### PCA Visualization:  

- The plot of PC1 shows that **Northern Ireland** significantly differs from England, Scotland, and Wales in food consumption patterns.  
- This result highlights unique dietary preferences in Northern Ireland compared to other UK regions.

---

## 🚀 Installation and Usage  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/uk-food-consumption-pca.git  
   cd uk-food-consumption-pca
2. Install dependencies:
    ```bash  
    pip install -r requirements.txt  
3. Run the analysis:
    ```bash  
    python pca_analysis.py
4. View the results:  
   - PCA plot and heatmaps will be displayed as output visualizations.  

---

## 🛠️ Tools and Libraries  

- **Programming Language:** Python  
- **Libraries:**  
  - `NumPy`  
  - `Pandas`  
  - `Matplotlib`  
  - `Seaborn`  

---

## 📜 License  

This project is licensed under the MIT License. See the `LICENSE` file for details.  

---

## 👤 Author  

**Your Name**  
- [GitHub](https://github.com/M-A-S1)  
- [LinkedIn](https://www.linkedin.com/in/m-a-s94/)
