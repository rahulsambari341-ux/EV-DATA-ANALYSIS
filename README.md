# EV-DATA-ANALYSIS
EV-DATA ANALYSIS
# EV Data Analysis Assignment

This project analyzes the **Electric Vehicle (EV) Population dataset** provided by the Washington State Department of Licensing (DOL). The dataset includes details about Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered in Washington.

## 📊 Project Overview

The goal of this project is to clean, explore, visualize, and model EV data to understand adoption patterns, vehicle characteristics, and regional trends.

### Key Steps:

1. **Data Cleaning**

   * Handled missing and zero values in `Base MSRP` and `Electric Range`.
   * Removed duplicate records.
   * Anonymized VINs while keeping them unique.
   * Cleaned and formatted vehicle location data.

2. **Data Exploration**

   * Identified the top 5 EV makes and models.
   * Analyzed EV distribution by county and city.
   * Studied adoption trends over different model years.
   * Calculated average electric range and base MSRP by model.
   * Checked percentage of vehicles eligible for CAFV incentives.

3. **Data Visualization**

   * Bar chart: Top 5 EV makes and models.
   * Heatmap/choropleth: EV distribution by county.
   * Line graph: EV adoption by year.
   * Scatter plot: Electric range vs. Base MSRP.
   * Pie chart: CAFV eligible vs. non-eligible vehicles.
   * Geospatial map: Registrations by vehicle location.

4. **Linear Regression Model**

   * Built a model to predict **Electric Range** using `Model Year`, `Base MSRP`, `Make`, and `Model`.
   * Achieved **R² ≈ 0.93**, showing strong prediction accuracy.
   * Found that base MSRP and make/model have strong influence on range.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/EV-Data-Analysis.git
   cd EV-Data-Analysis
   ```
2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook EV_ASSIGNMENT.ipynb
   ```

## 📌 Files in Repo

* `EV_ASSIGNMENT.ipynb` → Main Jupyter Notebook with full analysis.
* `Electric_Vehicle_Population_Data.csv` → Dataset used.
* `README.md` → Project details.

## 📈 Key Insights

* Tesla dominates EV registrations in Washington.
* King County has the highest adoption rate.
* EVs have good driving ranges, but prices vary widely.
* Incentives play an important role in adoption.
* Regression modeling helps predict the performance of new EVs.

## ✍️ Author

* **[Your Name]**
  Course Assignment – Electric Vehicle Data Analysis
