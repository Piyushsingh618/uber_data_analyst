# Uber Ride Data Analysis (Python, Pandas)

## Project Overview
This project focuses on analyzing Uber ride data to uncover patterns in ride usage, customer behavior, and operational trends. The objective is to perform data cleaning, exploratory data analysis (EDA), and visualization to derive actionable insights that can support business decision-making.

---

## Dataset
- **UberDataset.csv** – Raw dataset containing ride details  
- **UberDatasetCleaned.csv** – Processed dataset after data cleaning  

---

## Tools & Technologies
- Python (Pandas, NumPy)  
- Data Visualization (Matplotlib, Seaborn)  
- Jupyter Notebook  

---

## Key Steps Performed

### Data Cleaning & Preprocessing
- Handled missing values in relevant columns  
- Converted date columns into datetime format  
- Extracted useful features such as month, day, hour, and year  
- Removed redundant columns and structured the dataset  

### Feature Engineering
- Created new columns such as:
  - Month, Year, Day  
  - Start Hour, End Hour  
  - Trip Duration (in minutes)  

### Exploratory Data Analysis (EDA)
- Analyzed ride distribution by category (Business vs Personal)  
- Studied monthly and daily ride trends  
- Identified peak ride hours and demand patterns  
- Examined ride purposes and travel behavior  
- Evaluated total miles traveled across different time periods  

### Data Visualization
- Used bar plots, count plots, and heatmaps  
- Built a dashboard to represent key insights visually  

---

## Key Insights
- Peak ride demand observed during specific hours of the day (evening periods)  
- Business rides contribute significantly to total trips  
- Certain months show higher ride frequency indicating seasonal trends  
- Higher mileage trips are concentrated in specific time windows  

---

## Business Recommendations
- Optimize ride availability during peak demand hours  
- Introduce targeted strategies based on ride purpose and category  
- Improve operational efficiency by analyzing high-duration trips  
- Plan seasonal campaigns based on monthly ride trends  
- Focus on high-demand periods to improve service quality  

---

## Project Files
- `UberDataset.csv` – Raw dataset  
- `UberDatasetCleaned.csv` – Cleaned dataset  
- `Dashboard.png` – Visualization dashboard  
- `Uber_Rides_Data_Analysis.ipynb` – Complete analysis notebook  

---

## How to Run the Project

```bash
git clone https://github.com/yourusername/uber-rides-data-analysis.git
cd uber-rides-data-analysis
pip install -r requirements.txt
jupyter notebook Uber_Rides_Data_Analysis.ipynb
