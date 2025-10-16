# PRODIGY_DS_01 - TASK-01: World Bank Data Visualization

💬 **Project Overview**  
This project visualizes World Bank datasets (e.g., population, income, health indicators) and generates charts to explore top countries and trends over time.

**Key Features:**  
- Automatic detection of numeric year columns  
- Top 10 countries bar chart  
- Line chart for population/indicator trends over years  
- Handles datasets with extra/missing columns  

🗂️ **Dataset**  
- Sample dataset: Any World Bank CSV  
- Column detection: numeric year columns automatically detected  
- Can handle datasets with missing `Region` or `IncomeGroup` columns  

⚙️ **How to Run**  
1. Open `task01_visualization.ipynb` in Google Colab or Jupyter Notebook  
2. Upload your CSV file when prompted  
3. Run all cells to:  
   - Detect numeric year columns  
   - Generate top countries bar chart  
   - Generate population trend line chart  

📊 **Output**  
- **Top 10 Bar Chart** → Bar chart of top countries for selected year  
- **Trend Line Chart** → Population/indicator trends over years  

🛠️ **Libraries Used**  
- pandas  
- numpy  
- matplotlib  
- seaborn  

📌 **Notes**  
- Works with any World Bank CSV dataset  
- Auto-detects latest numeric year for plotting  
- Suitable for demographic, economic, or health indicator data  
