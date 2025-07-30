# Predicting Maize Production in Rwanda Using Big Data Analytics

## Assignment – INSY 8413: Introduction to Big Data  
**Name:** Niyonshimira Jeanmarie  
**Student ID:** 27197  
**Instructor:** Eric Maniraguha  
**Group:** A  

---

## Dataset Information

**Source:** [FAO.org – FAOSTAT Crops and Livestock Production](https://www.fao.org/faostat/en/#data/QC)  
**File Used:** `faostat_maize_rwanda_2020_2023.csv`  
**Country:** Rwanda  
**Years Covered:** 2020, 2021, 2022, 2023  
**Crop:** Maize  
**Columns:**  
`Year`, `Item`, `Country`, `Area Harvested`, `Yield`, `Production`  

---

## Data Cleaning & Feature Engineering

Data preparation was conducted using **Python in Jupyter Notebook**.

### Steps:  
1. Converted year column to proper datetime format  
2. Checked for missing and inconsistent data; applied imputation and corrections  
3. Detected and handled outliers to improve model accuracy  
4. Generated descriptive statistics for all features  
5. Created additional features to support modeling and visualization  

### Output Files:  
- `cleaned_maize_data.csv`: Cleaned dataset ready for analysis  
- `feature_engineered_maize_data.csv`: Dataset enhanced with engineered features  

---

## Power BI Dashboard

The cleaned dataset was imported into **Power BI** for visualization and reporting.

### Key Insights:  
- Maize production steadily increased from 2020 to 2023  
- Area harvested had a significant effect on yield variations  
- Seasonal and regional trends identified through interactive charts  
- Outlier years investigated for agricultural or climatic anomalies  

---

## Sample Visualizations

<img width="872" height="501" alt="loading the data " src="https://github.com/user-attachments/assets/7dc38c5b-c972-4a55-9861-978be5f47e8a" />


## dash board 
<img width="1024" height="1024" alt="the dashboard" src="https://github.com/user-attachments/assets/ec39a148-7203-4df2-b76c-1670b7c0c21c" />


---

## Conclusion

This project demonstrated the use of Python for data cleaning and machine learning, paired with Power BI for insightful visualization, to analyze and predict maize production trends in Rwanda. The results provide actionable insights to support agricultural planning and decision-making.

---

## License

This project is for academic purposes under **AUCA - INSY 8413**.  
Thank you for visiting this repository!
