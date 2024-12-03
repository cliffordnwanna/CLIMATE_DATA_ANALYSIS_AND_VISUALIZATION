# **Africa Climate Data Visualization and Analysis**

### **Project Overview**
This project focuses on exploring, cleaning, and visualizing climate data for several African countries from 1980 to 2023. Using Python and libraries like Pandas, Matplotlib, and Plotly, the project aims to uncover insights into temperature fluctuations, distributions, and trends, showcasing practical data analysis and visualization skills.

### **Key Features**
- **Data Exploration**: Initial exploration of the dataset to identify missing values, summary statistics, and data structure.
- **Data Cleaning**: Handling missing data using imputation methods and converting date columns to a suitable format for analysis.
- **Visualization**: Creating interactive and static visualizations to analyze:
  - Average temperature trends in Tunisia and Cameroon.
  - Temperature distributions in Senegal over different time ranges.
  - Average temperatures per country using aggregated data.
- **Insights and Interpretation**: Detailed observations and interpretations for each visualization to extract meaningful patterns.

### **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - **Data Manipulation**: Pandas
  - **Visualization**: Matplotlib, Plotly
- **Development Environment**: Google Colab

---

### **Setup Instructions**
1. Clone or download the repository.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib plotly
   ```
3. Load the dataset into the specified path or update the script with your dataset path.
4. Run the Python script in an IDE or environment supporting Jupyter Notebooks, such as Google Colab or JupyterLab.

---

### **Dataset**
Dataset : Africa_climate_change.csv
{ https://drive.google.com/file/d/1OpMcFl0xP7kvFr3Ljur2V_9SH5VhgLxl/view?usp=drive_link }
The dataset contains historical climate data for African countries with columns representing:
- **DATE**: The date in YYYYMMDD format.
- **COUNTRY**: The country of observation.
- **PRCP**: Precipitation levels.
- **TAVG**: Average temperature.
- **TMAX**: Maximum temperature.
- **TMIN**: Minimum temperature.

---

### **Analysis and Visualizations**
1. **Temperature Fluctuations**:
   - Line charts for average temperature trends in Tunisia and Cameroon (1980–2023 and 1980–2005).
   - Observations on climate changes over time.
   
2. **Temperature Distribution in Senegal**:
   - Histograms showing distributions for 1980–2000 and 2000–2023.
   - Comparative analysis to identify shifts in temperature patterns.

3. **Average Temperature by Country**:
   - Bar chart displaying average temperatures across all countries in the dataset.

---

### **Project Goals**
- Demonstrate data exploration and cleaning techniques.
- Showcase proficiency in creating meaningful visualizations.
- Provide actionable insights through data interpretation.

---

### **Future Improvements**
- Extend the analysis to include precipitation and other metrics.
- Integrate machine learning to predict future temperature trends.
- Develop a dashboard for real-time climate data visualization.

