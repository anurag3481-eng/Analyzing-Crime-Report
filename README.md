# 🕵️ Crime Data Analysis Dashboard

This project is an in-depth analysis and visualization of crime data using Python and Excel. It explores patterns in crime incidents based on time, method, location, and type, offering key insights for public safety awareness and law enforcement planning.

---

## 📊 Objectives

- Analyze crime distribution by time of day, method, and severity.
- Identify seasonal and yearly crime trends.
- Detect top crime hotspots geographically.
- Compare crime types across neighborhoods and shifts.

---

## 🗂️ Dataset Overview

- **Total Records**: ~35,000+
- **Time Period**: Includes Year, Month, and precise report times.
- **Features**:
  - `OFFENSE`: Type of crime (e.g., THEFT, ASSAULT, HOMICIDE)
  - `SHIFT`: Time shift (MIDNIGHT, DAY, EVENING)
  - `METHOD`: Mode used (e.g., GUN, KNIFE, OTHERS)
  - `WARD`, `BLOCK`, `NEIGHBORHOOD_CLUSTER`: Location details
  - `REPORT_DAT`, `START_DATE`, `END_DATE`: Date/time stamps

---

## 📈 Analysis Performed

### 1. Time of Day Analysis
- Crime frequency vs time of day
- Comparison across shifts: MIDNIGHT, DAY, EVENING

### 2. Crime Severity and Type
- Visual breakdown by offense type
- Severity clustering by method used (e.g., GUN-related incidents)

### 3. Yearly and Monthly Trends
- Year-over-year crime frequency
- Seasonality in offenses

### 4. Crime Hotspots
- Top 5 geographic hotspots identified
- Cluster analysis using `LATITUDE` and `LONGITUDE`

### 5. Method by Time of Day
- Most used methods during specific shifts

---

## 📌 Tools & Technologies

- **Python**: `pandas`, `matplotlib`, `seaborn`
- **Excel**: Dashboards, pivot tables, graphs
- **Jupyter/Streamlit (if extended)**: For interactive dashboards
- **Visualization**: Bar charts, line graphs, pie charts, geo heatmaps

---

## 🔍 Insights

- **Peak hours**: Evening shows the highest crime occurrence.
- **Common crimes**: THEFT and AUTO THEFT dominate.
- **Hotspots**: Specific neighborhoods consistently show high incident rates.
- **GUN-related crimes**: Mostly occur during late night or evening shifts.

---

## 🚀 How to Use

1. Clone the repository or download the project.
2. Open `12311288 anurag.xlsx` to explore sheets.
3. Run the analysis notebooks (optional) to reproduce visualizations.
4. Modify filters to analyze specific crime types, years, or areas.

---

## 📌 Future Enhancements

- Streamlit-based interactive dashboard
- Predictive modeling of crime trends
- Integration with real-time crime feeds

---

![image](https://github.com/user-attachments/assets/ad82dfc9-ae30-43eb-b6d7-8a631b35be7f)


